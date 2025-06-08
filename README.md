## What is NEXT.JS ?
* Next.js is a React framework for building full-stack web applicatiobn. Developed by Vercel and first released as an open source project on Github in 2016.
* So its means you can write any React code inside Next.js - like components, hooks, props, states--just like in a regular react app.
* And on top of that Next.js gives you everythintg that react doesn't provided out of the box- like routing, server-side rendering, static site generation, API routes, and even full backend logic- all in one powerful framework.

🏹 In simple Words
React gives you the frontend but Next.js give you the complete structure bulid production ready.

## Why Use NEXT.JS?
### 1. File-based Routing
* No Need for react-router-dom. Just create files inside the pages or app folder, and boom - route ready!

### 2. Performance - Optimization 
* Support Static generation and server side rendering - fast page loads and better SEO.

### 3. Build in API Routes
* You can write backend code like APIs right inside your NEzxt.js project. No need set up a separate server.

### 4. SEO Friendly
* Since it supports server rendering serch engines can read your content better.

### 5. Extra Optimization
* Images. Fonts, Metadata, Preloading etc

## Who Uses NEXT.JS?
1. NETFLIX, HULU, HBO
2. TWITCH
3. TIKTOK
4. OPENAI, REPL.IT, CLAUDE
5. TED, AUDIBLE
6. NIKE

## When To Choose NEXT.JS?
* Next.js is ideal for project where you need SEO optimization, fast loading times. or a mix of static and dynamic content. It's particularly well-suited for e-commerce sites, blogs, marketing website, and any application where performance and serch engine visibility matter.

## System Requirements
Before you begin, make sure ypur system meets the following requirements:
* Node.js 18.18 or later.
* macOs, Windows, or Linux
### 📌Automatic installation
npx create-next-app@latest

## App Folder Structure
![alt text](<REDME IMG/FS.png>)

### 🧩 What is layout.js?
* layout.js is a special file that wraps every page inside it.
* Every folder inside /app can have its own layout.js, making it a nested layout.
* Layouts are persistent — they do not remount between route changes (great for navigation bars, sidebars, etc.).

## Routes in NextJs
* If we want to create a routes in nextjs , it is very sime we createv a folder inside app then the route is creating but notes some point :   
 1. If we create only empty folder like service and not add anything then its give the error.
 2. If we create a folder name service and add a file inside it service.jsx and add some content then it again give error beacuge all file name will be page.jsx or page.tsx

 
## Nested Route in NextJs
* If you have folders inside folders, you create nested routes automatically.
![alt text](<REDME IMG/NextedRoutes.png>)

## 🧭 Link Component in Next.js
* In Next.js (not NestJS — which is a backend framework), the Link component is used for client-side navigation between pages. This is a core feature in Next.js that enables fast transitions without full-page reloads.
```.js
<Link href="/path">
  <a>Link Text</a> {/* for Next.js 12 and earlier */}
</Link>

<Link href="/path">Link Text</Link> {/* valid in Next.js 13+ */}

```