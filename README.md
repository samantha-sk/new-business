# Business Management System

A comprehensive business management system built with React and Node.js, featuring inventory management, billing, order tracking, and archive functionality.

## Features

### 1. Dashboard
- Real-time business metrics and KPIs
- Interactive charts and graphs
- Revenue trends and performance indicators
- Responsive design for all screen sizes

### 2. Inventory Management
- Product tracking and management
- Stock level monitoring
- Category-based organization
- Price range filtering
- Archive functionality for discontinued items
- Detailed product specifications

### 3. Billing System
- Invoice generation and management
- Payment tracking
- Multiple payment method support
- Tax calculation
- Discount management
- Receipt generation

### 4. Order Management
- Purchase order creation and tracking
- Warehouse integration
- Expected delivery date tracking
- Order status updates
- Detailed shipment tracking
- Product specifications per order

### 5. Archive System
- Comprehensive archiving for multiple item types:
  - Products
  - Orders
  - Invoices
  - Suppliers
  - Licenses
- Advanced filtering and search capabilities
- Date range filtering
- Type-based filtering
- Sorting options
- Export functionality (CSV, PDF, Excel)
- Restore and permanent deletion options
- Archive policy management

## Technical Stack

### Frontend
- **React.js** - UI framework
- **React Router** - Navigation and routing
- **CSS Modules** - Styling and component isolation
- **Chart.js** - Data visualization
- **React Icons** - Icon library
- **React Modal** - Modal dialogs
- **React Date Picker** - Date selection
- **React Table** - Data table management

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM for MongoDB
- **JWT** - Authentication
- **Bcrypt** - Password hashing
- **Cors** - Cross-origin resource sharing
- **Dotenv** - Environment variables

### Development Tools
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Git** - Version control
- **npm** - Package management
- **Webpack** - Module bundling
- **Babel** - JavaScript transpilation

## Project Structure

```
src/
├── components/
│   ├── shared/
│   │   ├── Sidebar.jsx
│   │   ├── Header.jsx
│   │   └── Footer.jsx
│   ├── Dashboard.jsx
│   ├── Inventory.jsx
│   ├── Billing.jsx
│   ├── Orders.jsx
│   └── Archive.jsx
├── styles/
│   ├── Dashboard.css
│   ├── Inventory.css
│   ├── Billing.css
│   ├── Orders.css
│   └── Archive.css
├── utils/
│   ├── api.js
│   └── helpers.js
└── App.jsx
```

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/business-management-system.git
```

2. Install dependencies:
```bash
cd business-management-system
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Start the development server:
```bash
npm start
```

5. Build for production:
```bash
npm run build
```

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```
REACT_APP_API_URL=http://localhost:5000
REACT_APP_MONGODB_URI=your_mongodb_uri
REACT_APP_JWT_SECRET=your_jwt_secret
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- React.js team for the amazing framework
- MongoDB team for the database solution
- All contributors and maintainers of the open-source packages used in this project #   n e w - b u s i n e s s  
 #   n e w - b u s i n e s s  
 