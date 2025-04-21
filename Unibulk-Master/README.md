

## Project Structure

The project consists of the following main components:

- **Frontend**: React-based web application
- **Backend**: Flask API server with MySQL database
- **iOS App**: Mobile application for iOS devices

## Features

- User authentication and account management
- Product catalog with detailed product information
- Bulk order processing
- Rating system for products
- Responsive design for various screen sizes

## Technology Stack

### Frontend
- React.js
- HTML/CSS
- JavaScript

### Backend
- Python (Flask)
- MySQL Database

### iOS App
- Swift/Objective-C

## Getting Started

### Prerequisites
- Node.js and npm/yarn
- Python 3.x
- MySQL Server
- Xcode (for iOS development)

### Backend Setup
1. Navigate to the backend directory:
   ```
   cd Unibulk-Master/backend
   ```
2. Install the required Python packages:
   ```
   pip install flask flask_sqlalchemy flask_cors
   ```
3. Configure your MySQL database credentials in `App.py`
4. Run the Flask server:
   ```
   python App.py
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```
   cd Unibulk-Master/frontend
   ```
2. Install dependencies:
   ```
   npm install
   ```
   or
   ```
   yarn install
   ```
3. Start the development server:
   ```
   npm start
   ```
   or
   ```
   yarn start
   ```

### iOS App Setup
1. Open the project in Xcode from the `ios_app` directory
2. Configure as needed
3. Build and run on a simulator or physical device

## API Endpoints

- `/users` - User authentication
- `/allProducts` - Get list of all products
- `/product/<id>` - Get details of a specific product

