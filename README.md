<img src="https://raw.githubusercontent.com/MiracleHorizon/scissors/main/apps/frontend/public/android-chrome-192x192.png" alt="Logo" width=128 height=128>

<h1 style="font-size: 32px; margin-top: 0">️Scissors</h1>

<p>
  Your awesome application for versatile image formatting and processing!
</p>

<a href="https://scissors-application.vercel.app" rel="noreferrer" target="_blank">Try it out</a>

## About The Project

The "Scissors" supports:

* 🌓 Dark mode
* 🎨 Theme color
* 💾 Export / import settings
* 📖 Documentation
* 🖼️ Gallery

### 🧨 Features

Some of the features available are:

* Rotation
* Resizing, Extending, Trimming
* Quality control
* Grayscale, Gammaize, Tint and other

Currently, the following image formats are supported:

* PNG
* JPEG / JPG
* WEBP

### 🔧 Technologies

* Next.js (App Router)
* Zustand
* Radix UI
* [Sharp](https://sharp.pixelplumbing.com/)
* Nest.js

### 📋 Requirements

* Node.js v20+
* pnpm

### 💻 Run locally

* Clone repository
   ```sh
   git clone https://github.com/MiracleHorizon/scissors.git
   ```
* Install NPM packages
   ```sh
   pnpm install --frozen-lockfile
   ```

* Build packages
   ```sh
   pnpm build:packages
   ```

* Run the project
   ```sh
   pnpm dev
   ```

### 🐳 Run with Docker

* Fill out the `.env` files for production mode

* Build
   ```sh
   docker-compose -f docker-compose.yaml build
   ```

* Run
   ```sh
   docker-compose -f docker-compose.yaml up
   ```

### License

Licensed under the MIT License, Copyright © 2023 - present [MiracleHorizon](https://github.com/MiracleHorizon).

See [LICENSE](https://github.com/MiracleHorizon/scissors/blob/main/LICENSE) for more information.

[project-github]: https://github.com/MiracleHorizon/scissors

[preview-screenshot-1]: social/og-image-share-light.png

[preview-screenshot-2]: social/og-image-share-dark.png
