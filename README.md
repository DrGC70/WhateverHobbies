The location of a life project: https://whatever-hobbies.vercel.app/sign-up.



![image](https://github.com/DrGC70/WhateverHobbies/assets/123336389/cf129cb7-1f75-4b19-9a2c-9effa24749b2)


# **Introduction**

Explore social media with this user-friendly platform that has a nice look and lots of features. Easily create and explore posts, and enjoy a strong authentication system and quick data fetching using React Query for a smooth user experience.

# **Tech Stack**

    - React.js
    - Appwrite
    - React Query
    - TypeScript
    - Shadcn
    - Tailwind CSS


# **Features**

👉 **Authentication System**: A robust authentication system ensuring security and user privacy

👉 **Explore Page**: Homepage for users to explore posts, with a featured section for top creators

👉 **Like and Save Functionality**: Enable users to like and save posts, with dedicated pages for managing liked and saved content

👉 **Detailed Post Page**: A detailed post page displaying content and related posts for an immersive user experience

👉 **Profile Page**: A user profile page showcasing liked posts and providing options to edit the profile

👉 **Browse Other Users**: Allow users to browse and explore other users' profiles and posts

👉 **Create Post Page**: Implement a user-friendly create post page with effortless file management, storage, and drag-drop feature

👉 **Edit Post Functionality**: Provide users with the ability to edit the content of their posts at any time

👉 **Responsive UI with Bottom Bar**: A responsive UI with a bottom bar, enhancing the mobile app feel for seamless navigation

👉 **React Query Integration**: Incorporate the React Query (Tanstack Query) data fetching library for, Auto caching to enhance performance, Parallel queries for efficient data retrieval, First-class Mutations, etc

👉 **Backend as a Service (BaaS) - Appwrite**: Utilize Appwrite as a Backend as a Service solution for streamlined backend development, offering features like authentication, database, file storage, and more

and many more, including code architecture and reusability

# **Quick Start**

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

    - Git
    - Node.js
    - npm (Node Package Manager)

**Cloning the Repository**

git clone https://github.com/DrGC70/WhateverHobbies.git

**Installation**

Install the project dependencies using npm:


    npm install


**Set Up Environment Variables**

Create a new file named .env in the root of your project and add the following content:

    VITE_APPWRITE_URL=

    VITE_APPWRITE_PROJECT_ID=

    VITE_APPWRITE_DATABASE_ID=

    VITE_APPWRITE_STORAGE_ID=

    VITE_APPWRITE_USER_COLLECTION_ID=

    VITE_APPWRITE_POST_COLLECTION_ID=

    VITE_APPWRITE_SAVES_COLLECTION_ID=


Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the Appwrite website.


**Running the Project**


    npm start


Open http://localhost:3000 in your browser to view the project.
