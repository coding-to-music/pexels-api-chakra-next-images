# pexels-api-chakra-next-images

# 🚀 Javascript full-stack 🚀

https://github.com/coding-to-music/pexels-api-chakra-next-images

https://pexels-api-chakra-next-images.vercel.app

by ASHUTOSH KUMAR SINGH https://github.com/lelouchB

https://next-image-gallery.vercel.app/

https://github.com/lelouchB/next-image-gallery

https://www.freecodecamp.org/news/build-an-image-gallery-with-nextjs/

https://www.pexels.com/api/new/

https://www.pexels.com/api/documentation/

## Environment Values

```java
vercel env add

NEXT_PUBLIC_PEXELS_API_KEY=""
```

## For daily cron job GitHub Action

```java
          curl --request POST \
          --url 'https://pexels-api-chakra-next-images.vercel.app/api/stats' \
          --header 'Authorization: Bearer ${{ secrets.APP_API_KEY }}'
```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/pexels-api-chakra-next-images.git
git push -u origin main
vercel --prod --confirm

# to add environment values:
# vercel env add
```

![Next Image Gallery](https://i.imgur.com/iPbBSce.png)

### Next Image Gallery [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2FlelouchB%2Fnext-image-gallery&env=NEXT_PUBLIC_PEXELS_API_KEY&envDescription=Pexels%20API%20Key%20&envLink=https%3A%2F%2Fwww.pexels.com%2Fapi%2Fnew%2F&project-name=next-image-gallery&repo-name=next-image-gallery)

An Image Gallery built with [Next.js](https://nextjs.org/) using [Pexels API](https://www.pexels.com/api/) and [Chakra UI v1](https://next.chakra-ui.com/).

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

Head over to https://www.pexels.com/api/new/ and create a new API key. Rename `.env.example` to `.env.local` and add the API key in it.

```
NEXT_PUBLIC_PEXELS_API_KEY =
```

Install the dependencies by running the following command.

```bash
npm install
```

Start the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
