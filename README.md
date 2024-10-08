# Memories Project - README

**Memories Project** is a full-stack **MERN** (MongoDB, Express.js, React.js, Node.js) application designed to help users share and explore memorable moments. The application allows users to create, view, edit, and delete memory posts, fostering a community where people can connect through shared experiences.

---

## 🚀 Features

- ✏️ **CRUD Operations**: Create, read, update, and delete memory posts.
- 📸 **Image Upload**: Users can attach images to their memory posts.
- 📱 **Responsive Design**: Optimized for both mobile and desktop devices.
- 🔗 **API Integration**: Backend built with **Express.js** and **MongoDB**.
- 🖥️ **Interactive Frontend**: Developed using **React.js** for a smooth user experience.

---

## 🛠️ Tech Stack

- **Frontend**: React.js, CSS, Material-UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ODM)
- **State Management**: Redux for global state management

---

## 🛠️ Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Lavoisier29/Memories_Project.git
    cd Memories_Project
    ```

2. **Install dependencies** for both the backend and frontend:
    - Backend:
      ```bash
      cd backend
      npm install
      ```
    - Frontend:
      ```bash
      cd ../frontend
      npm install
      ```

3. **Create a `.env` file** in the backend directory with the following details:
    ```env
    MONGO_URI=<Your MongoDB URI>
    JWT_SECRET=<Your JWT Secret>
    CLOUDINARY_API_KEY=<Your Cloudinary API Key>
    CLOUDINARY_API_SECRET=<Your Cloudinary API Secret>
    CLOUDINARY_CLOUD_NAME=<Your Cloudinary Cloud Name>
    PORT=5000
    ```

4. **Run the backend server**:
    ```bash
    cd backend
    npm start
    ```

5. **Run the frontend server**:
    ```bash
    cd ../frontend
    npm start
    ```

6. The app will be accessible at:
    - Frontend: [http://localhost:3000](http://localhost:3000)
    - Backend/API: [http://localhost:5000](http://localhost:5000)

---

## 📌 API Endpoints

- **GET** `/api/posts`: Retrieve all memory posts.
- **POST** `/api/posts`: Create a new memory post.
- **GET** `/api/posts/:id`: Retrieve a single post by ID.
- **PUT** `/api/posts/:id`: Update a memory post by ID.
- **DELETE** `/api/posts/:id`: Delete a memory post by ID.

---

## 📸 Image Upload (Cloudinary Integration)

The application integrates **Cloudinary** for storing images attached to posts. You will need to configure the Cloudinary API by setting up the `CLOUDINARY_API_KEY`, `CLOUDINARY_API_SECRET`, and `CLOUDINARY_CLOUD_NAME` in the `.env` file.

---

## 🤝 Contributing

Feel free to submit issues or pull requests to enhance the project. Contributions are always welcome!

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

