# Imagify - TextToImage

## Live Demonstration of the project
[Imagify : Click here to view](https://imagify-shozab.vercel.app/) <!-- Replace # with the actual live demo link -->

## About 
Imagify is an AI-powered image generating web application built on MERN stack. It integrates with the Clipdrop API to generate high-quality AI-generated images and includes a secure login/signup system.

---

## Features
- Intelligent image creation powered by the Clipdrop API.
- Built-in user access control with sign-up and login features.
- Minimalistic and clean UI, focusing on simplicity and user experience.

---

## Installation Instructions

1. Clone the repository:
```bash
git clone https://github.com/shozabali06/Imagify.git
```

2. Navigate to the project directory:
```bash
cd Imagify
```

### Server Setup

3. Navigate to the server folder:
```bash
cd server
```

4. Install dependencies:
```bash
npm install
```

5. Configure environment variables:
   Create a `.env` file in the `server` folder and add the following:
   ```env
   MONGODB_URI=<your-mongodb-connection-string>
   JWT_SECRET=<your-jwt-secret>
   CLIPDROP_API=<your-clipdrop-api-key>
   ```

6. Start the server:
```bash
npm run server
```

### Client Setup

7. Navigate to the client folder:
```bash
cd client
```

8. Install dependencies:
```bash
npm install
```

9. Configure environment variables:
   Create a `.env` file in the `client` folder and add the following:
   ```env
   VITE_BACKEND_URL=<url-for-server-side>
   ```

10. Start the client:
```bash
npm run dev
```

---

## Commands Summary

### Server Commands
- **Install dependencies:** `npm install`
- **Run the server:** `npm run server`

### Client Commands
- **Install dependencies:** `npm install`
- **Run the client:** `npm run dev`

---

