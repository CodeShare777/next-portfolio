This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Generate static webpages (SSG)
### Change build
Open `package.json`
and change build to 
```
"build": "next build && next export"
```
### Build and Export
```bash
npm run build
```
### Copy from out
Copy contents from `out` folder to the S3 bucket. 


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

