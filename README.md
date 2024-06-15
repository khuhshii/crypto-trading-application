
# Crypto Trading Application README

## Overview

This repository contains a crypto trading application developed using React, TypeScript, and Node.js. The application focuses on real-time stock rates generated using a random function. It integrates a third-party API for fetching stock names and details, implementing pagination for efficient data handling. The application is built with responsiveness and visual effects in mind to enhance user experience.

## Features

- **Real-Time Stock Rates**: Utilizes a random function to generate real-time stock prices.
- **Third-Party API Integration**: Fetches stock names and details from a third-party API.
- **Pagination**: Implements pagination to manage large datasets efficiently.
- **React Redux Thunk**: Utilizes Redux Thunk middleware for managing asynchronous state logic.
- **Vite Application**: Built as a Vite application for fast development and optimized builds.
- **Buying and Selling**: Includes features for buying and selling stocks within the application.

## Technologies Used

- **Frontend**: React, TypeScript, Redux, Redux Thunk
- **Backend**: Node.js
- **Build Tool**: Vite
- **API Integration**: Third-party APIs for stock details

## Getting Started

1. Clone the repository:
   ```
   git clone <repository_url>
   cd <project_directory>
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:3000` to view the application.


```
crypto-trading-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── StockList.tsx
│   │   ├── StockItem.tsx
│   │   └── ...
│   ├── pages/
│   │   ├── Dashboard.tsx
│   │   ├── BuyStock.tsx
│   │   └── SellStock.tsx
│   ├── store/
│   │   ├── actions/
│   │   │   ├── stockActions.ts
│   │   │   └── ...
│   │   ├── reducers/
│   │   │   ├── stockReducers.ts
│   │   │   └── ...
│   │   └── index.ts
│   ├── App.tsx
│   ├── index.tsx
│   ├── index.css
│   └── ...
├── package.json
├── tsconfig.json
└── README.md
```

## Development Guidelines

- Ensure all API interactions are handled asynchronously using Redux Thunk.
- Implement responsive design principles for optimal viewing across devices.
- Use Vite's fast refresh feature during development for quick feedback.
- Write clean and maintainable code following TypeScript best practices.
- Test thoroughly to ensure all buying, selling, and data fetching functionalities work as expected.

## Deployment

Deploy the application to a production environment using Vite's build command:
```
npm run build
```
This will create an optimized build of your application in the `dist/` directory ready for deployment.

## Images
## Contributing

Contributions are welcome! Fork the repository and submit a pull request for any improvements or fixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
