This is a [Next.js](https://nextjs.org/) project bootstrapped
with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## The goal

The target is to fetch data, handle errors and work carefully with the data to handle any edge cases that might happen.
The result should look like the image below:

![Target screen](target_screen.png?raw=true "Target screen")


- Fetch the JSON data from `/api/data`
- Handle any possible errors
- Calculate statistics for:
    1) Number of users who have invested
    2) Total invested amount
    3) Days until fundraising end (rounded up to full days)
    4) Value of an average investment
- Render the data in an opportunity card which has the same layout as the screenshot
- Display the statistics with max. 2 decimal places


Feel free to use any libs or tools you're comfortable with.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed
on [http://localhost:3000/api/data](http://localhost:3000/api/data). This endpoint can be edited
in `pages/api/data.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated
as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.
