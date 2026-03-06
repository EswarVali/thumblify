# Thumblify – AI Thumbnail Generator

Thumblify is an AI-powered web application that helps users generate high-quality thumbnails for videos instantly.  
It removes the need for manual design by using AI image generation and modern UI tools.

Users can generate thumbnails quickly and download them directly from the dashboard.

---

# Features

- AI-powered thumbnail generation
- Modern SaaS landing page
- User authentication system
- Thumbnail history dashboard
- Download generated thumbnails
- Cloud image storage
- Responsive UI
- 5 free thumbnail generations per user

---

# Tech Stack

## Frontend
- React
- TypeScript
- TailwindCSS
- Framer Motion
- React Router

## Backend
- Node.js
- Express
- MongoDB
- Mongoose

## AI & Media
- OpenAI Image Generation API
- Cloudinary Image Storage

---

# Screenshots

## Landing Page
![Landing](./screenshots/WhyUseOurs.png)

---

## Sign Up
![Signup](./screenshots/SignUpPage.png)

---

## Login
![Login](./screenshots/LoginPage.png)

---

## Homepage After Login
![Homepage](./screenshots/HomepageAfterLogin.png)

---

## Generate Thumbnail
![Generator](./screenshots/GeneratedThumbnails.png)

---

## Generating Thumbnail
![Generating](./screenshots/BeachHouseGenerating.png)

---

## Generated Result
![Result](./screenshots/BeachHouseGenerated.png)

---

## Open Generated Image
![OpenImage](./screenshots/OpeningDownladedImage.png)

---

## Download Thumbnail
![Download](./screenshots/DownloadOption.png)

---

## Pricing Plan
![Pricing](./screenshots/PricingPlan.png)

---

## Testimonials
![Testimonials](./screenshots/FakeTestimonials.png)

---

## Contact Section
![Contact](./screenshots/ContactUs.png)

---

## Footer
![Footer](./screenshots/Footer.png)

---

# Installation

Clone the repository

```bash
git clone https://github.com/EswarVali/thumblify.git
```

Go into the project directory

```bash
cd thumblify
```

---

## Backend Setup

Go to server folder

```bash
cd server
```

Install dependencies

```bash
npm install
```

Create a `.env` file in the **server folder**

```
MONGO_URI=your_mongodb_url
OPENAI_API_KEY=your_openai_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start backend server

```bash
npm run dev
```

---

## Frontend Setup

Go to client folder

```bash
cd client
```

Install dependencies

```bash
npm install
```

Run the frontend

```bash
npm run dev
```

The app will run at

```
http://localhost:5173
```

---

# Future Improvements

- Razorpay or Stripe subscription plans
- Unlimited thumbnail generation for Pro users
- Thumbnail editing tools
- Prompt history
- AI style presets

---

# Author

**Eswar Vali**

---

# License

This project is for learning and portfolio purposes.
