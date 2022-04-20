<h1 align="center">Medium Blog App<a href="https://medium-app.vercel.app/">Live Demo</a></h1>


### Project Preview

![](https://i.ibb.co/1zCQhSN/medium-app-vercel-app.jpg)
![](https://i.ibb.co/3rYGmgk/medium-app-vercel-app-1.jpg)

### Info

to start this project `git clone [this-git-repo]`
install all dependiencies by `npm i`
to start this project `npm start`
if you want to run it for production `npm run build`
change API keys with your own this for test only not built for production cases

### Project

Similar to Medium.com A fully responsive App Using tailwind css
typescript and sanity for the backend to create and consume API using
GROQ.
Fully Responsive and mobile first application using tailwind
Implement React Advanced concepts and use using next.js for static
regenerate
fetching API from sanity prepared I've built
Creating comment section using react hook form and tailwind CSS re-
render comment section using GROQ and fetching API from sanity
 __[Medium Blog App](https://medium-app.vercel.app/)

### Folder Structure

- Home
   - [README.md](README.md)
   - __components__
     - [Header.tsx](components/Header.tsx)
   - __mediumapp__
     - [README.md](mediumapp/README.md)
     - __config__
       - __@sanity__
         - [data\-aspects.json](mediumapp/config/@sanity/data-aspects.json)
         - [default\-layout.json](mediumapp/config/@sanity/default-layout.json)
         - [default\-login.json](mediumapp/config/@sanity/default-login.json)
         - [form\-builder.json](mediumapp/config/@sanity/form-builder.json)
         - [vision.json](mediumapp/config/@sanity/vision.json)
     - __dist__
       - [index.html](mediumapp/dist/index.html)
       - __static__
         - __css__
           - [main.css](mediumapp/dist/static/css/main.css)
         - [favicon.ico](mediumapp/dist/static/favicon.ico)
         - __js__
           - [app.bundle.js](mediumapp/dist/static/js/app.bundle.js)
           - [vendor.bundle.js](mediumapp/dist/static/js/vendor.bundle.js)
     - [node\_modules](mediumapp/node_modules)
     - [package\-lock.json](mediumapp/package-lock.json)
     - [package.json](mediumapp/package.json)
     - __plugins__
     - [sanity.json](mediumapp/sanity.json)
     - __schemas__
       - [author.js](mediumapp/schemas/author.js)
       - [blockContent.js](mediumapp/schemas/blockContent.js)
       - [category.js](mediumapp/schemas/category.js)
       - [comment.js](mediumapp/schemas/comment.js)
       - [post.js](mediumapp/schemas/post.js)
       - [schema.js](mediumapp/schemas/schema.js)
     - __static__
       - [favicon.ico](mediumapp/static/favicon.ico)
     - [tsconfig.json](mediumapp/tsconfig.json)
     - [yarn.lock](mediumapp/yarn.lock)
   - [next\-env.d.ts](next-env.d.ts)
   - [next.config.js](next.config.js)
   - [node\_modules](node_modules)
   - [package\-lock.json](package-lock.json)
   - [package.json](package.json)
   - __pages__
     - [\_app.tsx](pages/_app.tsx)
     - __api__
       - [createComment.ts](pages/api/createComment.ts)
       - [hello.ts](pages/api/hello.ts)
     - [index.tsx](pages/index.tsx)
     - __post__
       - [[slug].tsx](pages/post/%5Bslug%5D.tsx)
   - [postcss.config.js](postcss.config.js)
   - [prettier.config.js](prettier.config.js)
   - __public__
     - [favicon.ico](public/favicon.ico)
     - [vercel.svg](public/vercel.svg)
   - [sanity.js](sanity.js)
   - __styles__
     - [globals.css](styles/globals.css)
   - [tailwind.config.js](tailwind.config.js)
   - [tsconfig.json](tsconfig.json)
   - [typing.d.ts](typing.d.ts)
   - [yarn.lock](yarn.lock)
