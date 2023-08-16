# Instagram Clone

This project is an Instagram clone, a social media platform inspired by the popular photo-sharing platform. It utilizes Next.js version 13 for frontend development and an external API for the backend.

## Features

- User registration
- User login
- Image uploading
- User profiles
- Following other users
- Commenting and liking posts
- Explore and discover new posts
- Real-time notifications

## Technologies Used

- Next.js
- React.js
- Tailwind CSS
- GraphQL
- Apollo Client
- Firebase (for authentication and image storage)
- Socket.io (for real-time notifications)

## Prerequisites

- Node.js (version 16.20.0)
- npm (version 8.19.4)

## Installation

1. Clone this repository to your local machine:

   git clone https://github.com/carlosjmarq/Instagram-clone.git

2. Navigate to the project directory:

   cd instagram-clone

3. Install the dependencies:

   npm install

4. Set up the environment variables. Create a `.env.local` file in the root of the project and add the following variables:

   NEXT_PUBLIC_API_URL=https://api.example.com
   NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id

5. Start the development server:

   npm run dev

6. Open your browser and visit `http://localhost:3000` to see the running application.

## Contributing

Contributions are welcome! If you find any issues or have any suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. For more details, please refer to the [LICENSE](LICENSE) file.
Feel free to customize the content of the `README.md` file according to your project's specific needs.
