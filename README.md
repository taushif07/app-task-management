# app-task-management


// {
//     "builds": [
//       {
//         "src": "app.js",
//         "use": "@vercel/node"
//       },
//       {
//         "src": "build/**",
//         "use": "@vercel/static"
//       }
//     ],
//     "routes": [
//       {
//         "src": "/todos",
//         "dest": "app.js"
//       },
//       {
//         "src": "/products/(.*)",
//         "dest": "app.js"
//       },
//       {
//         "src": "/",
//         "dest": "build/index.html"
//       },
//       {
//         "src": "/(.+)",
//         "dest": "build/$1"
//       }
//     ],
//     "rewrites": [{ "source": "/(.*)", "destination": "index.js" }]
//   }