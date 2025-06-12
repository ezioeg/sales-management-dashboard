## 📊 Sales Management Dashboard  
Web application designed for efficient management of product sales. It enables creation of purchase orders and management of sellers, customers, products, offers, and inventory control.

### Features  
- **Purchase Order Management**: Create and manage purchase orders including seller, customer, and product details.  
- **Product Management**: Add, edit, and delete products from the inventory.  
- **Offers and Special Prices**: Manage offers and special pricing for products.  
- **Customer Management**: View and manage customer information.  
- **Inventory Control**: Maintain oversight of available inventory and its status.

## Technologies Used
### Core
- [React](https://reactjs.org/) `v17.0`
- [React Router](https://reactrouter.com/en/main) `v6 (beta)`

### UI/Styling
- [Tailwind CSS](https://tailwindcss.com/) `v2.0`
- [Rodal (modals)](https://github.com/chenjiahan/rodal) `v1.8`
- [React Icons](https://react-icons.github.io/react-icons/) `v4.1`
- [React Datepicker](https://reactdatepicker.com/) `v3.6`
- [TrendMicro React SideNav](https://github.com/TrendMicro-Frontend/react-sidenav) `v0.5`

### Forms & Validation
- [Formik](https://formik.org/) `v2.2`
- [Yup](https://github.com/jquense/yup) `v0.32`

### State Management
- [Context API](https://reactjs.org/docs/context.html)

### Backend as a Service
- [Firebase](https://firebase.google.com/) `v7.19` (Auth, Firestore, Storage)
- [React Firebase File Uploader](https://github.com/fris-fruitig/react-firebase-file-uploader) `v2.4.3`

## Setup
1. Install dependencies:

   ```bash
   npm install
   ```
2. Set up Firebase:

  * Create a project in Firebase and obtain the credentials.
  * Create a .env file in the root of the project and add your Firebase credentials.

## Run
To start the application in development mode, run:

   ```bash
   npm start
   ```
This will open the application in your default browser at http://localhost:3000.

## Contributions
Contributions are welcome. If you want to improve the project, please create a fork and submit a pull request.

## Contact
For questions or suggestions, you can contact me at [ezioeg@gmail.com].
