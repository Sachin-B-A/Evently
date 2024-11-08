<a name="readme-top"></a>

# Evently - Event Management Platform using Next.js 14

![Evently - Event Management Platform using Next.js 14]((https://github.com/sanidhyy/evently/raw/main/.github/images/img_main.png))


<!-- Table of Contents -->
<details>

<summary>

# : Table of Contents

</summary>

- [Folder Structure](#folder-structure)
- [Getting Started](#toolbox-getting-started)
- [Screenshots](#camera-screenshots)
- [Tech Stack](#gear-tech-stack)
- [Stats](#wrench-stats)
- [Contribute](#raised_hands-contribute)
- [Acknowledgements](#gem-acknowledgements)
- [Buy Me a Coffee](#coffee-buy-me-a-coffee)
- [Follow Me](#rocket-follow-me)
- [Learn More](#books-learn-more)
- [Deploy on Vercel](#page_with_curl-deploy-on-vercel)
- [Give A Star](#star-give-a-star)
- [Star History](#star2-star-history)
- [Give A Star](#star-give-a-star)

</details>

## : Folder Structure

Here is the folder structure of this app.

```bash
evently/
  |- app/
    |-- (auth)/
        |--- sign-in/[[...sign-in]]/
        |--- sign-up/[[...sign-up]]/
        |--- layout.tsx
    |-- (root)/
        |--- events/
            |---- [id]/update/
            |---- create/
        |--- orders/
        |--- profile/
        |--- layout.tsx
        |--- page.tsx
    |-- api/
        |--- uploadthing/
          |---- core.ts
          |---- route.ts
        |--- webhook/
          |---- clerk/
            |----- route.ts
          |---- stripe/
            |----- route.ts
    |-- favicon.ico
    |-- globals.css
    |-- layout.tsx
  |- components/
    |-- shared/
    |-- ui/
  |- config/
    |-- site.ts
  |- constants/
    |-- index.ts
  |- lib/
    |-- actions/
        |--- category.actions.ts
        |--- event.actions.ts
        |--- order.actions.ts
        |--- user.actions.ts
    |-- database/
        |--- models/
            |---- category.model.ts
            |---- event.model.ts
            |---- order.model.ts
            |---- user.model.ts
        |--- index.ts
    |-- uploadthing.ts
    |-- utils.ts
    |-- validator.ts
  |- public/assets/
    |-- icons/
    |-- images/
  |- types/
    |-- index.ts
  |- .env.example
  |- .env.local
  |- .gitignore
  |- components.json
  |- middleware.ts
  |- next.config.js
  |- package-lock.json
  |- package.json
  |- postcss.config.js
  |- tailwind.config.ts
  |- tsconfig.json
```

<br />

## :camera: Screenshots:

![Modern UI/UX](/.github/images/img1.png "Modern UI/UX")

![Search Events](/.github/images/img2.png "Search Events")

![Organize Events](/.github/images/img3.png "Organize Events")

![Buy Tickets](/.github/images/img4.png "Buy Tickets")

## :gear: Tech Stack

[![React JS](https://skillicons.dev/icons?i=react "React JS")](https://react.dev/ "React JS") [![Next JS](https://skillicons.dev/icons?i=next "Next JS")](https://nextjs.org/ "Next JS") [![Typescript](https://skillicons.dev/icons?i=ts "Typescript")](https://www.typescriptlang.org/ "Typescript") [![Tailwind CSS](https://skillicons.dev/icons?i=tailwind "Tailwind CSS")](https://tailwindcss.com/ "Tailwind CSS") [![Vercel](https://skillicons.dev/icons?i=vercel "Vercel")](https://vercel.app/ "Vercel") [![MongoDB](https://skillicons.dev/icons?i=mongodb "MongoDB")](https://mongodb.com/ "MongoDB")

## Getting Started

This is a Next.js project bootstrapped with `create-next-app`.

To start the development server, use one of the following commands:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
