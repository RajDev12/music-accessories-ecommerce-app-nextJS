# This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## API used=
- For Payments: [https://api.stripe.com/v1/payment_intents](https://api.stripe.com/v1/payment_intents)
- For Database: [https://www.sanity.io/learn/course/day-one-with-sanity-studio/creating-a-schema](https://www.sanity.io/learn/course/day-one-with-sanity-studio/creating-a-schema)

## Getting Started
First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file. [API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`. The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Deploy on Vercel
The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js. Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Steps to test on local environment
1. Run the following commands:
    - `npx create-next-app@latest myapp`
    - `npm install --legacy-peer-deps`
    - `import { urlFor } from '../../lib/client';`
    - `npm install react-icons`
2. Configure the stripe API for the payment gateway:
    - At line 18 of stripe.js, update project id
    - At line 15, update shipping rate and currency type
3. Press `ctrl+shift+I` to open inspect in Chrome

## Screenshots of the Webpages
![Screenshot Image](/public/webpageScreenshot/1.png)
![Screenshot Image](/public/webpageScreenshot/2.png)
![Screenshot Image](/public/webpageScreenshot/3.png)
![Screenshot Image](/public/webpageScreenshot/4.png)