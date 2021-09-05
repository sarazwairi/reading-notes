# Permissions & Postgresql

### APIView has two methods that check for permissions:

* check_permissions checks if the request should be permitted based on request data

* check_object_permissions checks if the request should be permitted based on the combination of the request and object data

### Object level permissions

REST framework permissions also support object-level permissioning. Object level permissions are used to determine if a user should be allowed to act on a particular object, which will typically be a model instance.

### API Reference



The AllowAny permission class will allow unrestricted access, regardless of if the request was authenticated or unauthenticated.

The IsAuthenticated permission class will deny permission to any unauthenticated user, and allow permission otherwise.

The IsAdminUser permission class will deny permission to any user, unless user.is_staff is True in which case permission will be allowed.

The IsAuthenticatedOrReadOnly will allow authenticated users to perform any request. Requests for unauthorised users will only be permitted if the request method is one of the "safe" methods; GET, HEAD or OPTIONS.

