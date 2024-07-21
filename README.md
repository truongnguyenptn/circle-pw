<br />
<div align="center">
  <a href="https://github.com/teyweikiet/circle-bounty-2-programmable-wallet" style="background: black; color: white;">
    <img src="frontend/app/favicon.ico" alt="Logo" width="40" height="auto" />
  </a>

  <h1 align="center" style="border-bottom: 0;">The Wallet App</h1>

  <p align="center">
    A fullstack Web 3 wallet app built with Circle’s Programmable Wallets.
    <br />
    <a href="https://circle-bounty-2-programmable-wallet.vercel.app/"><strong>View Demo</strong></a>
    <br />
  </p>
</div>

## About the project

## Features

- Wallet Creation - Users can easily create new wallet.

- Wallet Token Balances - Users can check balances of all tokens in their wallet.

- Wallet Transfers - Users can transfer tokens to another address by entering destination address. Alternatively, if user have saved the address in Contacts, they can just search them up by contact's name.

- Wallet PIN Update & Recovery - Users can change their PIN with current PIN. If they forgot their PIN, they can set new PIN with recovery options.

- Contacts - Users can save & label frequently used wallet address. Saved contacts will be searchable on "Destination Address" combobox in Transfer form so that user can transfer token by contact's name.

- Social Logins - Apart from email & password option, user can also easily sign up & login with Facebook.


## Instruction to take a quick tour of the app

1. Sign up with email & password or just use click on Login with Facebook button and login.

2. Create on circular plus button on the bottom right corner to create a new wallet. During the first time of creating wallet, you will be prompted to set up your PIN and fill up some recovery questions.

3. Add funds to your wallet via this [faucet](https://faucet.circle.com/).

4. Click on first tab ("Contacts") on the bottom navigation.

5. Click on circular plus button on the bottom right corner to add a new contact.

6. Go to second tab ("Wallets") on the bottom navigation. Click on wallet you have funded. And start transfer funds to another wallets. (Note: you will need native tokens to transfer funds. So be sure to add some native tokens to your wallet first.)

7. Go to third tab ("Settings") on the bottom navigation. You will be able to update your PIN by entering your current PIN. Or if you have forgotten your PIN, you can set new PIN by clicking "Forgot PIN" option.


## Built with

- [Circle](https://circle.com/)

- [Supabase](https://supabase.com/) - scalable, performant Backend as a Service powered by Postgres database - the world's most trusted relational database

- [Next.js](https://nextjs.org/)

- [Mantine](https://mantine.dev/)

- [Tanstack Query](https://tanstack.com/) - Powerful asynchronous state management, server-state utilities and data fetching.

- [Facebook Login](https://developers.facebook.com/products/facebook-login/)


## Running locally

- Clone the repo
- Install dependencies
- Make sure docker is running and start supabase locally
```sh
npm run supabase:start
```
- Apply migration
```sh
npm run supabase:migration:up
```
- Change directory to `/frontend` and install dependencies
```sh
cd frontend
npm i
```
- Set up `.env` by copying `.env.example` and modifying accordingly
```sh
cp .env.example .env
```
- Start frontend
```sh
npm run dev
```
# circle-pw
# circle-pw
