{
  "version": 2,
  "builds": [
    {
      "src": "index.js",
      "use": "@vercel/node"
    }
  ],
  "routes": [
    {
      "src": "/(.*)",
      "dest": "index.js"
    }
  ]
}
```

**Option 2: Rename `index.js` to `api/reviews.js`**

Vercel expects serverless functions in an `api/` folder. You could restructure like this:
```
/api
  /reviews.js  (just the /reviews endpoint)
  /accounts.js (just the /accounts endpoint)
  /locations.js (just the /locations endpoint)
