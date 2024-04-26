This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


# Starting With Project

### Create the necessary Folder
- app
- components
- models
- publi/assets
- styles (add globals.css file and add the styling in that)
- utils

### Create files in app folder
- layout.jsx
- page.jsx

** Importing files: '@folder_in_root_directory/filename'
- example: '@styles/globals.css'

** remove / from path in jsconfig.js

** Complete the page.jsx and layout.jsx of app folder

** Connect to DB

** Create user Model

** Create auth api
- go to console.cloud.google.com
- create project
- create credential (OAuth)
- create session, signIn function 

** Go to openssl terminal (online) and run command to generate random secret to encrypt 

### Create new Prompt
- create prompt model if does not exist
- create folder create-prompt in app/api folder
- create the create-prompt form ui
- create the api/prompt/new/route.js (POST api to create new prompt)
- connect the create-prompt form with the api

** We will need to use connectToDB() everytime a new api is made


