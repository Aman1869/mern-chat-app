# ChatterHive

A full-stack real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with socket.io integration for seamless real-time communication.  

## Features  
- **User Authentication**: Secure login and signup using JWT and bcrypt.  
- **Real-Time Messaging**: Chat functionality with instant message updates using Socket.IO.  
- **Responsive Design**: Fully responsive UI built with React, TailwindCSS, and DaisyUI.  
- **Cloud Media Storage**: Image uploads and storage powered by Cloudinary.  
- **Theming Options**: Multiple UI themes powered by DaisyUI.  

## Tech Stack  

### Backend  
- **Node.js**  
- **Express.js**  
- **Socket.IO**  
- **MongoDB (Mongoose)**  
- **Cloudinary**  
- **JWT for authentication**  

### Frontend  
- **React.js**  
- **Zustand** (State Management)  
- **TailwindCSS** and **DaisyUI** (Styling)  
- **Vite** (Build Tool)  

---

## Directory Structure  

```plaintext  
mern-chat-app/  
├── backend/  
│   ├── src/  
│   │   ├── controllers/  
│   │   ├── lib/  
│   │   ├── models/  
│   │   ├── routes/  
│   │   ├── middleware/  
│   │   └── index.js  
│   ├── package.json  
│   └── package-lock.json  
├── frontend/  
│   ├── src/  
│   │   ├── components/  
│   │   ├── store/  
│   │   ├── pages/  
│   │   ├── lib/  
│   │   ├── constants/  
│   │   └── sounds/  
│   ├── tailwind.config.js  
│   ├── package.json  
│   ├── vite.config.js  
│   └── index.html  
└── package.json  
```  

---

## Installation and Setup  

1. **Clone the repository**  
   ```bash  
   git clone https://github.com/Aman1869/mern-chat-app.git  
   cd mern-chat-app  
   ```  

2. **Backend Setup**  
   - Navigate to the backend directory:  
     ```bash  
     cd backend  
     ```  
   - Install dependencies:  
     ```bash  
     npm install  
     ```  
   - Create a `.env` file in the `backend` directory with the following variables:  
     ```plaintext  
     PORT=5000  
     MONGO_URI=your_mongodb_connection_string  
     JWT_SECRET=your_secret_key  
     CLOUDINARY_URL=your_cloudinary_url  
     ```  
   - Start the backend server:  
     ```bash  
     npm run dev  
     ```  

3. **Frontend Setup**  
   - Navigate to the frontend directory:  
     ```bash  
     cd frontend  
     ```  
   - Install dependencies:  
     ```bash  
     npm install  
     ```  
   - Start the frontend development server:  
     ```bash  
     npm run dev  
     ```  

4. **Run the Application**  
   - Open your browser and navigate to:  
     ```plaintext  
     http://localhost:5173  
     ```  

---

## License  
This project is licensed under the MIT License.  
