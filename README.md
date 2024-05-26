# MERN Blog Application

A full-stack blog application built using the MERN stack (MongoDB, Express, React, Node.js).

## Features

- User authentication and authorization
- Create, read, update, and delete blog posts
- Rich text editor for writing blog posts
- Comment on blog posts
- User profiles
- Responsive design

## Technologies Used

- **Frontend:** React, Axios
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT, bcrypt
- **Styling:** CSS, Bootstrap

## Getting Started

### Prerequisites

- Node.js and Yarn installed on your machine
- MongoDB installed and running

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/dejwid/mern-blog.git
    cd mern-blog
    ```

2. **Install dependencies for the backend:**
    ```sh
    cd api
    yarn install
    ```

3. **Install dependencies for the frontend:**
    ```sh
    cd /client
    yarn install
    ```

### Configuration

1. **Backend Configuration:**

    Create a `.env` file in the `backend` directory and add the following variables:
    ```env
    MONGO_URI=your_mongo_db_uri
    JWT_SECRET=your_jwt_secret
    PORT=5000
    ```

2. **Frontend Configuration:**

    Create a `.env` file in the `frontend` directory and add the following variables:
    ```env
    REACT_APP_API_URL=http://localhost:5000/api
    ```

### Running the Application

1. **Start the backend server:**
    ```sh
    cd backend
    yarn start
    ```

2. **Start the frontend development server:**
    ```sh
    cd ../frontend
    yarn start
    ```

    The application will be available at `http://localhost:3000`.

### Scripts

- **Backend:**
  - `yarn start` - Start the backend server
  - `yarn run dev` - Start the backend server with nodemon
- **Frontend:**
  - `yarn start` - Start the frontend development server
  - `yarn build` - Build the frontend for production

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


