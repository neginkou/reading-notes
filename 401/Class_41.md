# React 4

Understanding how Next.js handles static file serving and the default folder structure for storing static assets is important for developing Next.js applications efficiently. By knowing where and how to store static assets, developers can easily include images, fonts, and other resources in their applications without worrying about complex configuration or performance issues.

[Next.js - Dynamic Routes](https://nextjs.org/learn/basics/dynamic-routes)

[Next.js - Deployment](https://nextjs.org/learn/basics/deploying-nextjs-app)

[Next.js 10 is here](https://www.youtube.com/watch?v=JWCS5IdECVI)

[Next.js - Static File Serving](https://nextjs.org/docs/basic-features/static-file-serving)

1. Explain the concept of dynamic routes in Next.js and how they differ from static routes.

Dynamic routes in Next.js allow pages to be created based on URL parameters, like [id].js for a product page. They render content dynamically based on the URL. Static routes, on the other hand, are pre-rendered at build time and have fixed URLs with content that doesn't change frequently.

2. Describe the process of deploying a Next.js application. What are the key steps involved, and what are some deployment platforms you can use?

* Build: Use next build to create a production build.
* Choose a platform: Select a hosting platform like Vercel, AWS Amplify, Netlify, or Heroku.
* Configuration: Set up environment variables and other settings for your platform.
* Deployment: Use the platform's interface or CLI to deploy your app.
Monitor: Keep an eye on performance and manage updates through the platform.

3. How does Next.js handle static file serving? Discuss the default folder structure for storing static assets and explain how to reference them in a Next.js application.

Next.js handles static file serving by using the /public directory in the project. Any files placed in the /public directory are served at the root of your website.

For example, a file named favicon.ico placed in the /public directory can be accessed at `http://yourwebsite.com/favicon.ico`.