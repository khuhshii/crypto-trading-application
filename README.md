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
![310256535-1ef4d469-1c84-4c28-a008-68303d25727a](https://github.com/khuhshii/crypto-trading-application/assets/116865740/0daabb26-dfd3-43c7-9c22-98b87f55d315)

![310256541-4fbdeb23-921a-47cf-bda0-89309dbaf44c](https://github.com/khuhshii/crypto-trading-application/assets/116865740/e2c5c5ff-3b37-47d7-a642-8e6687783297)

![310256556-9cb5c41c-c14c-436b-bc91-2ff665aec050 (1)](https://github.com/khuhshii/crypto-trading-application/assets/116865740/c769f6e7-2250-400b-8e48-affe80fce152)

![310256567-a71e52f6-4f4f-4fed-be3d-a1ec0f23cc30](https://github.com/khuhshii/crypto-trading-application/assets/116865740/1a60bd76-9be7-4faa-a40e-647fb9301d9f)

![310263210-e4bd8d19-5ab6-4ae2-9b5c-9c16400d61d8](https://github.com/khuhshii/crypto-trading-application/assets/116865740/88573489-fed7-4866-be98-475bd047cd84)

## Contributing

Contributions are welcome! Fork the repository and submit a pull request for any improvements or fixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
