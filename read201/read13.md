# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

* Native client applications have the advantage when it comes to persistent local storage.
* Cookies can be used for persistent local storage of small amount of data.

# The DOwnsides of Cookies

* cookies slow down your web application.
* cookies send unencrypted data over the internet.
* cookies are limited to 4kb of data.
* ideally , we want to be able to store lots of data on the client and have it persist beyond page 
refresh and not be transmitted to the server .

# HTML5 Storage

* web storage , local storage , DOM storage
* store key/value pairs locally within the client web browser 
* data persists but is never transmitted to remote web server
* most recent versions of browsers support HTML5 storage

# Checking for HTML5 storage
```
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```
Using modernizr

```
if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}
```
# Using HTML5 Storage

* stored in named key/value pairs
* data is stored as string
* use functions like parselnt() or parseFloat() to coerce retrieved data
```
interface Storage {

getter any getItem(in DOMString key);

setter creator void setItem(in DOMString key, in any data);

};
```
* calling setltem() will overwrite pervious value if it already exists
* calling getltem() will return null if doesnt exist
* you can treat localstorage object as an associateive array
```
var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);
```
## Square brackets syntax
```
var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;
```
removing values
```
interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
```
get total amount of values stored 
```
interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index);
};
```
# tracking changes

* event is fired on the window object whenever setltem(), removeltem() 
or clear() is called and a change is made 

* you can track these changes by adding an event listener to the window 

```
if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};


* callback function will called with StorageEvent object

function handle_storage(e) {
  if (!e) { e = window.event; }
}
```
# limitiation

* each origin gets 5 megabytes by default 
* " QUOTA_EXCEEDED_ERR" exception thrown if you exceed storage quota

# HTML5 storage in action 

```
function saveGameState() {
    if (!supportsLocalStorage()) { return false; }
    localStorage["halma.game.in.progress"] = gGameInProgress;
    for (var i = 0; i < kNumPieces; i++) {
	localStorage["halma.piece." + i + ".row"] = gPieces[i].row;
	localStorage["halma.piece." + i + ".column"] = gPieces[i].column;
    }
    localStorage["halma.selectedpiece"] = gSelectedPieceIndex;
    localStorage["halma.selectedpiecehasmoved"] = gSelectedPieceHasMoved;
    localStorage["halma.movecount"] = gMoveCount;
    return true;
}
};
```

** all codes snippets are from the following article .

http://diveinto.html5doctor.com/storage.html

























