# DalleGen: MERN Stack AI Image Generator

## ✨ Project Overview

DalleGen is a full-stack web application that leverages the power of Artificial Intelligence to generate unique images from textual prompts, similar to OpenAI's DALL·E. Built with the MERN (MongoDB, Express.js, React, Node.js) stack, this application allows users to unleash their creativity by describing an image, having the AI bring it to life, and then sharing it with a community.

## 🛠️ Technologies Used

* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **AI Integration:** OpenAI API (DALL·E)
* **Optional:** Cloudinary (for image storage)

## 🚀 Features

* **Text-to-Image Generation:** Describe any image and see it generated using AI.
* **Community Sharing:** Share your creations with others on a public feed.
* **Responsive Design:** Works smoothly on all screen sizes.
* **Simple UI:** Clean, intuitive interface powered by Tailwind CSS.

## 📋 Prerequisites

Before starting, make sure you have:

- Node.js (LTS version)
- npm (Node Package Manager)
- MongoDB (local or Atlas)
- Git
- OpenAI API Key

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/harrisrais/Dalle-Replica.git
cd Dalle-Replica
cd server
npm install
MONGODB_URL=YOUR_MONGODB_CONNECTION_STRING
OPENAI_API_KEY=YOUR_OPENAI_API_KEY
# CLOUDINARY_CLOUD_NAME=YOUR_CLOUDINARY_CLOUD_NAME
# CLOUDINARY_API_KEY=YOUR_CLOUDINARY_API_KEY
# CLOUDINARY_API_SECRET=YOUR_CLOUDINARY_API_SECRET
PORT=8080
npm start
