# Book Store

This is a Book Store application built using HTML, CSS, JavaScript, Node.js, Express, and MongoDB.

## Features

- **User Authentication**: Sign up, login, and profile management
- **Book Catalog**: Browse and search for books
- **Shopping Cart**: Add books to cart and proceed to checkout
- **Payment Integration**: Support for payment via Stripe
- **Admin Panel**: For managing books, users, and orders

## Technologies Used

- Frontend: HTML, CSS, JavaScript, React
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)
- Payment Gateway: Stripe
- Others: Redux for state management, Axios for API calls

## Setup Instructions

1. Clone the repository
   ```bash
   git clone https://github.com/YourUsername/book-store.git
   ```

2. Navigate to the project folder
   ```bash
   cd book-store
   ```

3. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```

4. Install dependencies for the frontend:
   ```bash
   cd frontend
   npm install
   ```

5. Set up environment variables:
   - Create a `.env` file in the backend directory and configure necessary variables like `MONGODB_URI`, `JWT_SECRET`, `STRIPE_SECRET_KEY`, etc.

6. Run the development server:
   - For the backend:
     ```bash
     npm run dev
     ```
   - For the frontend:
     ```bash
     npm start
     ```

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
