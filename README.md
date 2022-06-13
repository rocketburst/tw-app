
# Twitter Clone

This is a clone of Twitter to show off my frontend development skills!

## Authors

- [@rkazi103](https://www.github.com/rkazi103)


## Tech Stack

**Client:** Next JS, TailwindCSS, Twitter API

**Server:** Sanity CMS


## Features

- Authentication using Twitter Account
- Full Tweeting functionality with the ability to add comments
- Mobile first responsive design
- Toast Notifications for excellent UX


## Demo

_Coming Soon_

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`NEXT_PUBLIC_PROJECT_ID`

`NEXT_PUBLIC_SANITY_DATASET`

`SANITY_API_TOKEN`

`NEXT_PUBLIC_BASE_URL`

`TWITTER_CLIENT_ID`

`TWITTER_CLIENT_SECRET`

`NEXTAUTH_SECRET`

`NEXTAUTH_URL`
## Run Locally

Clone the project

```bash
  git clone https://github.com/rkazi103/tw-app
```

Go to the project directory

```bash
  cd tw-app
```

Install Next JS dependencies

```bash
  yarn
```

Install Sanity CMS dependencies

```bash
npm i -g @sanity/cli
cd src/studio && yarn
```

Start Next JS Server

```bash
  yarn dev
```

Start Sanity Studio

```bash
cd src/studio 
sanity login
sanity start
```