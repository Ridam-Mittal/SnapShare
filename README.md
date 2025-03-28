# SnapShare

A full-stack photo-sharing platform built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) with features like image uploads, user authentication, comments, and image editing.

## Features

- **User Authentication:** Secure authentication using JWT and cookies.
- **Photo Uploads:** Users can upload, share, and manage images.
- **Comments:** Commenting system for user interaction.
- **Image Editing:** Integrated with ImageKit for resizing, cropping, and applying filters.
- **Infinite Scrolling:** Seamless user experience with efficient data loading.
- **Responsive Design:** Optimized for both desktop and mobile screens.

## Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Image Management:** ImageKit
- **Authentication:** JWT and Cookies

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Ridam-Mittal/SnapShare.git
   cd SnapShare
   ```

2. **Install Dependencies:**

   ```bash
   cd client
   npm install
   cd ../backend
   npm install
   ```

3. **Set Environment Variables:**
   Create a `.env` file in the backend directory with the following:

   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   IMAGEKIT_URL=your_imagekit_url
   IMAGEKIT_PUBLIC_KEY=your_public_key
   IMAGEKIT_PRIVATE_KEY=your_private_key
   ```

4. **Run the Application:**

   - **Backend:**
     ```bash
     cd backend
     npm run dev
     ```
   - **Frontend:**
     ```bash
     cd client
     npm start
     ```

5. **Access the App:**
   Open your browser and navigate to `http://localhost:3000`.

##

