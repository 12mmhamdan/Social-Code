# Social-Code

Social-Code is a dynamic social media platform that allows users to create profiles, connect with others, and share various types of content such as text, images, and videos. This project is a collaborative effort between myself and Kevin McClain. The platform is built using a modern technology stack to ensure a responsive and interactive user experience.

## Live Demo

You can access the live demo of Social-Code [here](https://social-code-8h5u.onrender.com/).

## Features

- **User Profiles**: Create and customize personal profiles.
- **Content Sharing**: Post text, images, and videos.
- **Connections**: Connect with other users and view their posts.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technology Stack

### Front-end

- **React.js**: Used for building the user interface and providing a responsive and interactive experience.
- **State Management**: Redux or similar state management libraries are employed to manage the application's state effectively.

### Back-end

- **Express.js**: Handles server-side logic and API endpoints.
- **Node.js**: Provides the server environment for running the application.

### Database

- **MongoDB**: Used as the database to store user profiles, posts, messages, and other data.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/12mmhamdan/social-code.git
    cd social-code
    ```

2. **Install dependencies for both the front-end and back-end**:
    ```bash
    # Front-end
    cd client
    npm install

    # Back-end
    cd ../server
    npm install
    ```

3. **Set up environment variables**:
    - Create a `.env` file in the `server` directory and add your MongoDB URI and any other necessary environment variables:
      ```bash
      MONGO_URI=your_mongo_db_uri
      JWT_SECRET=your_jwt_secret
      ```

4. **Run the development server**:
    - Start the back-end server:
      ```bash
      cd server
      npm run dev
      ```
    - Start the front-end server:
      ```bash
      cd ../client
      npm start
      ```

5. **Open your browser**:
    - Navigate to `http://localhost:3000` to see the application in action.

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure your code adheres to the project's coding standards and is well-documented.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Kevin McClain for collaboration and contributions to the project.
- The open-source community for providing essential tools and libraries.

For any questions or support, please contact us at [hamdanmoataz@gmail.com].
