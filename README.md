# Fullstack Twitch Clone: Next.js 14, Livestreaming, React, Prisma, Stripe, Tailwind, PostgreSQL

### Prerequisites

**Node version 18.17 or later**

### Cloning the repository

```shell
git clone https://github.com/JC4F/Twitch-Clone.git
```

### Install packages

```shell
pnpm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
CLERK_WEBHOOK_SECRET=

DATABASE_URL=

LIVEKIT_API_URL=
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_WS_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```

### Setup Prisma

Add PostgreSQL Database (I used NEON)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
pnpm dev
```

or

```shell
pnpm build
pnpm start
```
