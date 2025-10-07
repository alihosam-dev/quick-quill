# QuickQuill

[Live Demo](https://quick-quill-gold.vercel.app/)

QuickQuill is a full-featured blogging platform built with the MERN stack (MongoDB, Express, React, Node.js). It allows users to create accounts, manage profiles, write and publish blog posts, and interact with other users. The project is designed as a summer passion project, focusing on providing a seamless and engaging experience for bloggers and readers.

## Features

- **User Authentication**: Secure account system with support for Google OAuth and traditional email/password login.
- **Profile Management**: Users can set up a personal bio, connect social links, and set a profile image.
- **Blog Creation & Management**: Easily compose, edit, and publish blog posts with rich-text editing tools and media uploads (integrated AWS S3 support).
- **Content Interaction**: Blog cards display stats such as views and other metrics; readers can browse posts and author profiles.
- **Responsive UI**: Built using React and Vite for fast rendering and smooth navigation.
- **RESTful API**: Express.js backend handles all user, blog, and content management operations.
- **Minimal Design**: The frontend is streamlined for clarity and ease of use, with custom components for blog posts, notifications, loaders, and more.

## Technologies Used

- **Frontend**: React, Vite, React Router, custom hooks and components, Editor.js for rich-text editing, Tailwind CSS for styling.
- **Backend**: Node.js, Express.js, MongoDB (via Mongoose), AWS S3 for image uploads.
- **Authentication**: JWT, Google OAuth.
- **Other Tools**: ESLint, Babel, SWC (for fast refresh in development).

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/alihosam-dev/quick-quill.git
   ```
2. **Install dependencies:**
   - Frontend: Navigate to the `frontend` folder and run `npm install`.
   - Backend: Navigate to the `server` folder and run `npm install`.

3. **Set up environment variables:**
   - Backend requires MongoDB URI, AWS credentials, and other secrets.

4. **Run the development servers:**
   - Frontend: `npm run dev` (in the `frontend` directory)
   - Backend: `npm start` or `node api/index.js` (in the `server` directory)

## Folder Structure

- `frontend/`: React + Vite frontend source code.
- `server/`: Express.js backend API and MongoDB schemas.

## Contributing

Pull requests, issues, and feedback are welcome! Please open an issue for suggestions or bug reports.

## License

This project is licensed under the terms of the MIT license.

---

> *QuickQuill is a summer passion project by [alihosam-dev](https://github.com/alihosam-dev).*
