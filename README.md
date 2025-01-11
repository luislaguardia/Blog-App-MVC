# Blog App (MVC)

![License](https://img.shields.io/badge/license-MIT-blue.svg)

Welcome to the **Blog App** repository! This application is built using the MVC (Model-View-Controller) architecture to demonstrate efficient and clean software design. The app allows users to create, edit, and manage blog posts seamlessly.

## Features

- Create, read, update, and delete blog posts.
- MVC architecture for separation of concerns.
- Responsive and user-friendly interface.
- EJS templating for dynamic views.
- Easily extensible for future features.

## Tech Stack

- **Backend:** Node.js with Express.js
- **Templating Engine:** EJS
- **Frontend:** HTML, CSS
- **Database:** MongoDB (requires local or remote MongoDB instance)

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance)
- A code editor like VS Code

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/luislaguardia/Blog-App-MVC.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Blog-App-MVC
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Configure the database:

   - Create a `.env` file in the root directory with the following content:

     ```env
     MONGODB_URI=mongodb://localhost:27017/blogApp
     PORT=3000
     ```

   - Replace `mongodb://localhost:27017/blogApp` with your MongoDB connection string if using a remote instance.

5. Start the application:

   ```bash
   npm start
   ```

6. Open your browser and navigate to:

   ```
   http://localhost:3000
   ```

## Usage

- To create a new blog post, click the **New Post** button on the dashboard.
- Edit or delete posts using the respective buttons next to each post.
- Navigate through posts using pagination (if implemented).

## Project Structure

```plaintext
Blog-App-MVC
├── controllers/   # Application logic
├── models/        # Database schema and queries
├── views/         # UI templates (EJS files)
├── public/        # Static files (CSS, images)
├── routes/        # Application routes
├── app.js         # Main application file
├── .env           # Environment variables
├── package.json   # Node.js dependencies
└── README.md      # Project documentation
```

## Contribution

Contributions are welcome! Please follow the steps below:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add new feature"
   ```

4. Push the branch:

   ```bash
   git push origin feature-name
   ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, feel free to reach out:

- **Author:** Luis Gabriel Lagurdia
- **Email:** laguardialuisgabriel@gmail.com
- **GitHub:** [luislaguardia](https://github.com/luislaguardia)

---

Thank you for checking out this project! Happy coding!
