# Car Sales Management System

A modern web application for managing car sales, inventory, and customer information.

## Features

- Dashboard with key metrics
- Inventory management
- Sales tracking
- Customer management
- Responsive design
- Modern UI with Material-UI components

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd car-sales-management
```

2. Install dependencies:
```bash
npm install
```

## Development

To start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## Building for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` directory.

## Project Structure

```
car-sales-management/
├── public/
│   └── car.svg
├── src/
│   ├── components/
│   │   └── Layout.tsx
│   │   ├── pages/
│   │   │   ├── Dashboard.tsx
│   │   │   ├── Inventory.tsx
│   │   │   ├── Sales.tsx
│   │   │   └── Customers.tsx
│   │   ├── App.tsx
│   │   ├── main.tsx
│   │   └── index.css
│   ├── index.html
│   ├── package.json
│   ├── tsconfig.json
│   └── vite.config.ts
```

## Technologies Used

- React
- TypeScript
- Material-UI
- Vite
- React Router
- Formik
- Yup

## License

MIT 