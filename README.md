This project uses Tailwind CSS (v3.3.3) with Next.js. It follows the steps outlined in the official Tailwind docs here: https://tailwindcss.com/docs/guides/nextjs.

## Required tools:

1. Next JS
2. Tailwind CSS
3. Alchemy NFT API
4. Alchemy Account

#### How to use:

##### Set-up app
```bash
create-next-app
# with
npm
# like so:
npx create-next-app --example_app_name with-tailwindcss with-tailwindcss-app
```
##### Adjust tailwind.config file according to the tailwind docs linked above
##### Open server to get the localhost url for your next.js front end
```
npm run dev
```

### Set-up Alchemy API

1. Create a new app with Alchemy. Copy the API KEY into your .env file
2. Go to Alchemy getNFTs endpoint https://docs.alchemy.com/reference/getnfts for your BaseURL in the fetch functions
3. Repeat no.2 for getNFTsForCollection https://docs.alchemy.com/reference/getnftsforcollection

##### Use opensea.io to get nft collection addresses
