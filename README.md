# Photofy
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)


## [Overview](#overview)
This project is an AI-powered Software as a Service (SaaS) application for image editing. Built using Next.js, it leverages Cloudinary for image storage and manipulation, Clerk for user authentication, Stripe for payment processing, and MongoDB for data management.

## [Features](#features)
- **AI Image Editing**: Utilize advanced AI algorithms to enhance and edit images.
- **User Authentication**: Secure user sign-up and login using Clerk.
- **Payment Integration**: Seamless payment processing with Stripe.
- **Image Storage**: Efficient image storage and delivery through Cloudinary.
- **Database Management**: Store user data and image metadata in MongoDB.

## Technologies Used
- **Next.js**: A React framework for server-side rendering and static site generation.
- **Cloudinary**: A cloud-based service for image and video management.
- **Clerk**: User authentication and management service.
- **Stripe**: Payment processing platform.
- **MongoDB**: NoSQL database for data storage.

## [Installation](#installation)
1. Clone the repository:
   ```bash
   git clone https://github.com/nasaomar165/photofy.git
   ```
2. Navigate to the project directory:
   ```bash
   cd photofy
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables in a `.env` file:
   ```plaintext
     #NEXT
     NEXT_PUBLIC_SERVER_URL=
   
     #MONGODB
     MONGODB_URL=
      
     #CLERK
     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
     CLERK_SECRET_KEY=
     WEBHOOK_SECRET=

     #CLERK ROUTES
     NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
     NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
     NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
     NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
   
     #CLOUDINARY
     NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
     CLOUDINARY_API_KEY=
     CLOUDINARY_API_SECRET=
   
     #STRIPE
     STRIPE_SECRET_KEY=
     STRIPE_WEBHOOK_SECRET=
     NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```

## [Usage](#usage)
- Visit `http://localhost:3000` in your browser to access the application.
- Sign up or log in to start editing images.

## [Contributing](#contributing)
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.
