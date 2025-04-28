# WhisperWire Frontend

A modern chat application frontend built with **React 19**, **Vite**, **Tailwind CSS**, and **Socket.IO**.

> **Note**: The frontend code for this application can be found in the [WhisperWire Backend Repository](https://github.com/Garvit-Adlakha/WhisperWire-backend).

## Features

- ⚡ Fast development with Vite
- 🎨 Styled with Tailwind CSS and DaisyUI
- 🔥 React 19 with SWC for fast refresh
- 🌐 Google OAuth support
- 📦 State management with Zustand and React Query
- 🔌 Real-time communication via Socket.IO
- 🍞 Toast notifications with react-hot-toast
- 🧩 Emoji picker, icons, and more

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/WhisperWire-frontend.git
   cd WhisperWire-frontend
   ```

2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

3. Create a `.env` file in the project root (see example below).

### Environment Variables

Example `.env`:
```
VITE_API_BASE_URL=http://localhost:5001/api/v1
VITE_API_URL=http://localhost:5001/
VITE_GOOGLE_CLIENT_ID=your-google-client-id
```

### Development

Start the development server:

```sh
npm run dev
# or
yarn dev
```

The app will be available at [http://localhost:3000](http://localhost:3000).

### Build

To build for production:

```sh
npm run build
# or
yarn build
```

### Preview Production Build

```sh
npm run preview
# or
yarn preview
```

### Linting

```sh
npm run lint
# or
yarn lint
```

## Project Structure

- `/src` - Main source code
- `/public` - Static assets
- `/dist` - Production build output

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)
- [Socket.IO](https://socket.io/)
- [Zustand](https://zustand-demo.pmnd.rs/)
- [React Query](https://tanstack.com/query/latest) for server state management and data fetching
- [Chart.js](https://www.chartjs.org/)
- [Google OAuth](https://developers.google.com/identity)

## License

MIT © 2025 Garvit Adlakha

---

_This project was bootstrapped with [Vite](https://vitejs.dev/) and uses [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) for fast refresh._
