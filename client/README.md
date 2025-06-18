# E-commerce Chat Helper Agent

A React application that demonstrates an e-commerce website with an integrated chat helper agent to assist customers with their shopping experience.

## Features

### Chat Helper Agent
- Floating chat widget that can be toggled open/closed
- Simulated AI responses based on user queries
- Quick reply buttons for common questions
- Product recommendations within the chat
- Typing indicators for a more natural experience

### E-commerce Store Frontend
- Modern, responsive design
- Product listings with cards
- Sale and "New" badges
- Interactive navigation
- Shopping cart and wishlist indicators

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository or download the source code
2. Navigate to the project directory:
   ```
   cd ecommerce-chat-helper
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Start the development server:
   ```
   npm start
   ```
5. Open your browser and navigate to `http://localhost:3000`

## Project Structure

- `src/components/ChatWidget.js` - The floating chat helper component
- `src/components/ProductCard.js` - Reusable product card component
- `src/components/EcommerceStore.js` - Main e-commerce store layout

## Customization

### Chat Responses
To customize the chat responses, modify the `generateResponse` function in `ChatWidget.js`. You can add more conditional logic to handle different types of user queries.

### Product Data
The sample product data is defined in `EcommerceStore.js`. Replace this with your actual product data or connect to an API.

## Future Enhancements

- Connect to a real NLP/AI backend for more intelligent responses
- Implement user authentication
- Add product search functionality within the chat
- Enable product filtering and sorting
- Implement a complete checkout flow
- Add order tracking integration

## License

MIT
