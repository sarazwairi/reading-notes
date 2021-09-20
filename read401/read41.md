#   React 4

### Dynamic Routes

npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/dynamic-routes-starter"

You should also update the following files:

* public/images/profile.jpg with your photo (Recommended: 400px width/height).
* const name = '[Your Name]' in components/layout.js with your name.
* <p>[Your Self Introduction]</p> in pages/index.js with your self introduction.



Then Nextjs Dynamic Routes exports a Link component. It's just like next/link, but it adds a route prop that let you refer to a route by its name.



You can benefit from that by simply putting a prefetch property on any Link :

```
<Link prefetch route="film" id="2"><a>The Empire Strikes Back</a></Link>
```

### Deploying Your Next.js App

npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/basics-final"

follow these steps:

1. Sign up to Vercel (no credit card is required).

2. After signing up, you’ll arrive on the “Import Project” page. Under “From Git Repository”, choose the Git provider you use and set up an integration. (Instructions: GitHub / GitLab / BitBucket).

3. Once that’s set up, click “Import Project From …” and import your Next.js app. It auto-detects that your app is using Next.js and sets up the build configuration for you. No need to change anything — everything should work fine!

4. After importing, it’ll deploy your Next.js app and provide you with a deployment URL. Click “Visit” to see your app in production.


