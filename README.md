<div align="center">
  <a href="https://github.com/truongnguyenptn/circle-pw">
    <img src="frontend/app/favicon.ico" alt="Logo" width="40" height="auto" />
  </a>

  <h1 align="center">The Wallet App</h1>

  <p align="center">
    A complete Web 3 wallet solution utilizing Circle’s Programmable Wallets.
    <br />
    <a href="https://circle-pw.vercel.app/"><strong>View Demo</strong></a>
  </p>
</div>

## Overview

The Wallet App is a robust Web 3 wallet designed with Circle’s Programmable Wallets, providing a seamless way for users to manage their digital assets.

## Key Features

- **Create Wallets**: Simple wallet creation process.
- **View Balances**: Check balances of various tokens in your wallet.
- **Transfer Tokens**: Send tokens to any address or use saved contacts for quick transfers.
- **Update & Recover PIN**: Change your PIN or recover it using security questions.
- **Manage Contacts**: Save and label frequently used wallet addresses.
- **Social Login Options**: Sign up and log in with Facebook or email and password.

## Getting Started

### Quick Start Guide

1. **Register or Log In**: Sign up with your email and password or log in using Facebook.
2. **Create a Wallet**: Click the plus button at the bottom right to create a new wallet. Set your PIN and recovery questions on the first creation.
3. **Fund Your Wallet**: Add funds using the [faucet](https://faucet.circle.com/).
4. **Add Contacts**: Go to the "Contacts" tab and add new contacts using the plus button.
5. **Transfer Funds**: In the "Wallets" tab, select a wallet to transfer funds. Ensure you have native tokens for transactions.
6. **Update PIN**: In the "Settings" tab, update your PIN or recover it using the "Forgot PIN" option.

## Tech Stack

- **Circle**: [Circle](https://circle.com/)
- **Supabase**: [Supabase](https://supabase.com/), a scalable backend powered by Postgres.
- **Next.js**: [Next.js](https://nextjs.org/)
- **Mantine**: [Mantine](https://mantine.dev/)
- **Tanstack Query**: [Tanstack Query](https://tanstack.com/), for asynchronous state management and data fetching.
- **Facebook Login**: [Facebook Login](https://developers.facebook.com/products/facebook-login/)

## Running the Project Locally

Follow these steps to set up and run the project locally:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/truongnguyenptn/circle-pw.git
    ```

2. **Install Project Dependencies**:
    ```sh
    npm install
    ```

3. **Start Supabase Locally**:
    Ensure Docker is running, then start Supabase:
    ```sh
    npm run supabase:start
    ```

4. **Apply Database Migrations**:
    ```sh
    npm run supabase:migration:up
    ```

5. **Set Up Frontend**:
    Navigate to the frontend directory and install dependencies:
    ```sh
    cd frontend
    npm install
    ```

6. **Configure Environment Variables**:
    Copy the example environment variables file and adjust as needed:
    ```sh
    cp .env.example .env
    ```

7. **Start the Frontend Application**:
    ```sh
    npm run dev
    ```
