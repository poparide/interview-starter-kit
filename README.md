# Poparide frontend interview

## Setup

- Install **Node.js 22** (`nvm use` reads `.nvmrc`)
- Install **Expo Go** on your phone, or use an iOS Simulator / Android emulator
- **iPhone only:** create a free account at [expo.dev](https://expo.dev), sign
  in to it in Expo Go, and run `npx expo login` in `apps/mobile` with the same
  account
- From the repo root, run `npm install`

## Run

- `npm run dev`
- Your phone must be on the same Wi-Fi as your computer
- **iPhone:** scan the QR code with the Camera app, or open the project under
  "Development servers" in Expo Go
- **Android:** scan the QR code in Expo Go
- **Simulator:** select the `mobile#dev` task, press `i` to interact, then
  `i` (iOS) or `a` (Android)
- If something looks stale, reload with `r`, or clear the cache with
  `cd apps/mobile && npx expo start -c`
