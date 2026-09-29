# Haven mobile

Expo + React Native + TypeScript starter for the follow-on mobile client. This is a discovery-only shell; account flows and mobile listing management are future work. It uses the same `/api/v1/listings` endpoint as the web app and displays local demo content when the API cannot be reached.

## Run locally

Install Node.js 20+ and pnpm, then run `pnpm install` and `pnpm start`. Copy `.env.example` to `.env` and set `EXPO_PUBLIC_API_URL` to an API address reachable from your simulator/device. For a physical phone, `localhost` refers to the phone; use your development machine's LAN address.
