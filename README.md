# CartWish Frontend

Frontend application for **CartWish**, an e-commerce platform that allows users to browse products, manage their shopping cart, and place orders.

This application communicates with the **CartWish Backend API** to fetch product data, manage authentication, and handle cart and order operations.

---

## Features

- User registration and login
- Browse products
- Add products to cart
- Remove products from cart
- Update cart quantities
- Checkout and place orders
- Responsive user interface
- Integration with backend REST API

---

## Tech Stack

This project uses the following technologies:

- React.js
- JavaScript (ES6+)
- HTML5
- CSS3
- Axios / Fetch API
- React Router
- Node Package Manager (npm)

---

## Project Structure

```
cartwish-frontend
│
├── public/             # Static files
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Page components
│   ├── services/       # API service functions
│   ├── styles/         # CSS styles
│   ├── App.js          # Root component
│   └── index.js        # Entry point
│
├── package.json
└── README.md
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Erick-Ry/cartwish-frontend.git
cd cartwish-frontend
```

### 2. Install dependencies

```bash
npm install
```

---

## Environment Variables

Create a `.env` file in the root directory:

```
REACT_APP_API_URL=http://localhost:5000
```

This should point to the CartWish backend API.

---

## Running the Application

Start the development server:

```bash
npm start
```

The application will run on:

```
http://localhost:3000
```

---

## Backend Repository

This frontend connects to the CartWish backend API.

Backend repository:  
https://github.com/Erick-Ry/cartwish-backend

---

## Build for Production

To create a production build:

```bash
npm run build
```

This will generate optimized files inside the `build/` folder.

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Author

Developed by **Erick Ry**

GitHub:  
https://github.com/Erick-Ry
