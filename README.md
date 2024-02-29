# Adding Passkey Login to Remix with Hanko

This repo shows how you can add passkey login with Hanko Passkey API to your Remix app.

## Clone the repo

```bash
git clone https://github.com/teamhanko/remix-passkeys.git
```

## Add the environment variables

Add the following environment variables to `.env.local` file.

```sh
PASSKEYS_API_KEY=your-hanko-passkey-api-key
PASSKEYS_TENANT_ID=your-hanko-passkey-tenant-id
```

## Install dependencies

```bash
pnpm install
```

## Run the project

```bash
pnpm run dev
```
