# HTTRiRi

![screenshot of HTTRiRi website](public/homepage-screenshot.png)

Explore HTTP status codes with this collection of Rihanna GIFs. Each GIF links to the relevant https://httpstatuses.com/ page.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, install the dependencies:

```bash
npm install 
# or 
yarn
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Adding a New Status Code
- The GIF should include Rihanna and not already be included on https://www.httriri.com/. Project maintainers reserve the right to determine whether or not a particular Rihanna GIF reflects the status code in question.
- New GIFs should be added to the `/public/images` folder and named like [statuscode].gif
- The statuses file should be updated to include the new status code in `statuses`  https://github.com/M0nica/httriri/blob/master/utils/statuses.ts

- For status code 404. I added a new image `404.gif` to `/public/images` and updated statuses.ts to include:
``` {
    code: 404,
    title: "Not Found",
    description:
      "Rihanna singing Story of my life Searching for the right But it keeps avoiding me",
  },
 ```
 
Note the code, title and description (which is used for [image alt text](https://developer.mozilla.org/en-US/docs/Web/API/HTMLImageElement/alt) are all required. The title should match the title on https://httpstatuses.com/ for that particular status code. 

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
