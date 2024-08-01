# Podcast Web Application

## Description
This is a Podcast Web Application built using React.js for the front-end and MongoDB for the back-end database. The application allows users to explore, listen to, and manage podcasts in an intuitive and user-friendly interface. The front-end is styled using Tailwind CSS.

## Features
- **User Authentication**: Sign up, log in, and manage your profile.
- **Podcast Streaming**: Stream podcasts directly from the web app.
- **Podcast Management**: Add, edit, and delete your podcasts.
- **Search & Discover**: Easily search for podcasts or explore featured content.

## Installation

### Prerequisites
Ensure you have the following installed on your system:
- Node.js (with npm)
- MongoDB

### Steps to Set Up

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/podcast-web-app.git
    cd podcast-web-app
    ```

2. **Set Up the Front-end**:
    ```bash
    cd client
    npm install
    npm run dev
    ```

3. **Set Up the Back-end**:
    ```bash
    cd ../server
    npm install
    npm start
    ```

4. **Environment Variables**:
   Create a `.env` file in the root of the server directory and add your MongoDB URI and any other necessary configuration variables:
    ```bash
    MONGO_URI=your_mongodb_uri_here
    PORT=5000
    ```

5. **Run the Application**:
   The front-end will be running on `http://localhost:3000` and the back-end on `http://localhost:5000`.

   You can now access the application by visiting `http://localhost:3000` in your browser.

## Technologies Used

### Front-end:
- React.js
- Tailwind CSS

### Back-end:
- Node.js
- Express.js
- MongoDB

### Other Tools:
- npm for package management
- MongoDB Atlas (optional for cloud database)

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add your feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.



## Contact

If you have any questions or feedback, please feel free to reach out.

- **Email:** vishalbharathonly@gmail.com
- **GitHub:** [vishalbharath](https://github.com/vishalbharath)
