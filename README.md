# QuickBlog – Smart Thoughts Turned into Blogs

## Project Overview

QuickBlog is a full-stack blogging platform that allows users to read blogs, engage through comments, and interact with dynamically generated content. The platform includes a powerful admin dashboard for managing blogs and moderating user comments.

The application integrates the Google Gemini AI API to automatically generate blog content from a simple title prompt, making content creation faster and smarter. ImageKit is used for optimized image uploads and delivery across devices, ensuring a responsive and high-performance blogging experience.

---

## Key Features

🔹 **AI Blog Content Generation**  
Generate blog content instantly from a title prompt using the Google Gemini AI API.

🔹 **Blog Reading Platform**  
Users can browse and read blogs with a clean and responsive interface.

🔹 **Comment System**  
Users can add comments to blogs, encouraging interaction and discussion.

🔹 **Admin Dashboard**  
Admins can generate, publish, edit, and delete blogs from a dedicated dashboard.

🔹 **Comment Moderation**  
Admins can monitor and manage user comments to maintain content quality.

🔹 **Image Optimization**  
Integrated ImageKit for efficient image uploads, transformations, and fast delivery.

🔹 **Responsive User Interface**  
Designed a modern and responsive UI using React.js and Tailwind CSS.

---

## Tech Stack

### Frontend Technologies

🔹 React.js  
🔹 Tailwind CSS  

### Backend Technologies

🔹 Node.js  
🔹 Express.js  

### Database

🔹 MongoDB  

### API Integrations

🔹 Google Gemini API – AI Blog Content Generation  
🔹 ImageKit.io – Image Uploads and Optimization  

---

## Application Workflow

🔹 Admin enters a blog title in the dashboard.  
🔹 The backend sends the title prompt to the Gemini AI API.  
🔹 AI generates blog content automatically.  
🔹 Admin can review, edit, and publish the blog.  
🔹 Images are uploaded and optimized using ImageKit.  
🔹 Users can read blogs and add comments.  
🔹 Admin moderates and manages comments from the dashboard.

---

## Project Structure

```
QuickBlog
│
├── client
│   ├── public
│   └── src
│       ├── assets
│       ├── components
│       ├── pages
│       └── context
│
├── server
│   ├── controllers
│   ├── routes
│   ├── models
│   ├── middleware
│   └── config
│
└── README.md
```

---

## Installation and Setup

### 1. Clone the repository

```
git clone https://github.com/yourusername/quickblog.git
```

### 2. Navigate to the project folder

```
cd quickblog
```

### 3. Install backend dependencies

```
cd server
npm install
```

### 4. Install frontend dependencies

```
cd client
npm install
```

---

### 5. Environment Variables

Create a `.env` file inside the **server** folder and add:

```

JWT_SECRET = 'your_key'
ADMIN_EMAIL = "your_email"
ADMIN_PASSWORD = "your_password"
MONGODB_URI = "your_mongodb_url"
IMAGEKIT_PUBLIC_KEY = "your_imagekit_public_key"
IMAGEKIT_PRIVATE_KEY = "your_imagekit_private_key"
IMAGEKIT_URL_ENDPOINT = "your_imagekit_url_endpoint"
GEMINI_API_KEY = "your_gemini_key_id"

```

---

### 6. Run the Backend Server

```
npm run server
```

### 7. Run the Frontend Application

```
npm run dev
```

---

## Learning Outcomes

🔹 Built a full-stack blogging platform with modern technologies  
🔹 Integrated AI-powered content generation using Gemini API  
🔹 Implemented image upload and optimization using ImageKit  
🔹 Designed an admin dashboard for blog and comment management  
🔹 Developed RESTful APIs using Node.js and Express  
🔹 Created a responsive UI using React.js and Tailwind CSS  

---

## Author

**Shafiya Uzama Vadulapalli**  
Full Stack Developer
