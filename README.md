# Poetic Echoes

![Poetic Echoes](https://cloud-ppyu19102-hack-club-bot.vercel.app/0_c4363f81-a2df-41ba-bfc1-60cb252df085.jpeg)

<div align="center">

  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248" alt="mongodb" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Clerk-black?style=for-the-badge&logoColor=white&logo=clerk&color=6C47FF" alt="clerk" />
    <img src="https://img.shields.io/badge/-Shadcn_UI-black?style=for-the-badge&logoColor=white&logo=shadcnui&color=000000" alt="shadcnui" />
    <img src="https://img.shields.io/badge/-Zod-black?style=for-the-badge&logoColor=white&logo=zod&color=3E67B1" alt="zod" />
    <img src="https://img.shields.io/badge/-Typescript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
  </div>
  </br>
</div>

Poetic Echoes is a social media platform designed for discovering and sharing poetry. It provides a space for poets and poetry enthusiasts to connect, engage, and explore the world of poetry. This README.md file provides an overview of the project structure, features, and credits.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Credits](#credits)

## Features

- **User Authentication**: Poetic Echoes uses [Clerk](https://clerk.dev/) for user authentication, providing a secure and seamless login experience.
- **Threaded Discussions**: Users can create and participate in threaded discussions, allowing for in-depth conversations and replies.
- **Search Functionality**: The search feature allows users to find specific posts or threads based on keywords or tags.
- **Profile Pages**: Each user has a profile page where they can showcase their posts and engage with other users.
- **Activity Feed**: The activity feed provides users with updates on recent posts, comments, and interactions.
- **Responsive Design**: The site is fully responsive, ensuring a seamless experience across different devices and screen sizes.

## ⚙️ Tech Stack

- Next.js
- MongoDB
- Shadcn UI
- TailwindCSS
- Clerk
- Webhooks
- Serverless APIs
- React Hook Form
- Zod
- TypeScript

## 🔋 Features

👉 **Authentication**: Authentication using Clerk for email, password, and social logins (Google and GitHub) with a comprehensive profile management system.

👉 **Visually Appealing Home Page**: A visually appealing home page showcasing the latest threads for an engaging user experience.

👉 **Create Posts Page**: A dedicated page for users to create posts, fostering community engagement

👉 **Commenting Feature**: A commenting feature to facilitate discussions within posts.

👉 **Nested Commenting**: Commenting system with nested posts, providing a structured conversation flow.

👉 **User Search with Pagination**: A user search feature with pagination for easy exploration and discovery of other users.

👉 **Activity Page**: Display notifications on the activity page when someone comments on a user's thread, enhancing user engagement.

👉 **Profile Page**: User profile pages for showcasing information and enabling modification of profile settings.

👉 **Blazing-Fast Performance**: Optimal performance and instantaneous page switching for a seamless user experience.

👉 **Server Side Rendering**: Utilize Next.js with Server Side Rendering for enhanced performance and SEO benefits.

👉 **MongoDB with Complex Schemas**: Handle complex schemas and multiple data populations using MongoDB.

👉 **File Uploads with UploadThing**: File uploads using UploadThing for a seamless media sharing experience.

👉 **Real-Time Events Listening**: Real-time events listening with webhooks to keep users updated.

👉 **Middleware, API Actions, and Authorization**: Utilize middleware, API actions, and authorization for robust application security.

👉 **Next.js Layout Route Groups**: New Next.js layout route groups for efficient routing

👉 **Data Validation with Zod**: Data integrity with data validation using Zod

👉 **Form Management with React Hook Form**: Efficient management of forms with React Hook Form for a streamlined user input experience.

and many more, including code architecture and reusability improvements.

## Project Structure

The project follows a modular structure, with different components and pages organized into separate files. Here is an overview of the main files and directories:

- `components`: Contains reusable components used throughout the site, such as `ThreadCard`, `Bottombar`, `Topbar`, etc.
- `app/(root)`: Contains the main pages of the application, including the home page, profile page, and thread page.
- `constants`: Contains constants used throughout the application, such as sidebar links and profile tabs.
- `layout.tsx`: Defines the layout of the site, including the top bar, sidebars, and bottom bar.
- `globals.css`: Contains global CSS styles used throughout the site.

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/devsrijit/poetic-echoes.git
cd threads
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
MONGODB_URL=
CLERK_SECRET_KEY=
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
NEXT_CLERK_WEBHOOK_SECRET=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up for the corresponding websites on [MongoDB](https://www.mongodb.com/), [Clerk](https://clerk.com/), and [Uploadthing](https://uploadthing.com/). 

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.