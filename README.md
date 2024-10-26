
---

# Drug Inventory and Supply Chain Tracking System

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Future Scope](#future-scope)
- [Contributing](#contributing)
- [License](#license)

---

## About the Project

The **Drug Inventory and Supply Chain Tracking System** is designed to streamline the management, tracking, and distribution of drugs and pharmaceuticals. This system enhances transparency, reduces errors, and helps ensure drugs are available to those who need them. It serves as a centralized platform to manage inventory, track shipments, and monitor supply chains.

## Features

- **Real-Time Inventory Management**: Monitor drug availability and stock levels.
- **Supply Chain Tracking**: Track shipments from manufacturers to distributors and retail points.
- **Alerts and Notifications**: Automated alerts for low stock, shipment delays, and expiration warnings.
- **Reporting and Analytics**: Generate reports on inventory, sales, and distribution patterns.
- **Role-Based Access Control**: Admin, distributor, and retailer roles to control access and permissions.

## Technology Stack

- **Backend**: Python (Flask/Django)
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Other**: REST APIs for data handling

## Installation

### Prerequisites
- Python 3.8+
- MySQL

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Drug-Inventory-Tracking-System.git
   cd Drug-Inventory-Tracking-System
   ```

2. **Create a virtual environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure the Database**
   - Create a MySQL database named `DBMS3`.
   - Update the database configuration in the project’s settings file.

5. **Apply Migrations**
   ```bash
   python manage.py migrate
   ```

6. **Run the Server**
   ```bash
   python manage.py runserver
   ```

7. **Access the application**
   - Open your browser and go to `http://localhost:8000`.

## Usage

1. **Admin Panel**: Add new drugs, manage inventory, and view analytics.
2. **Inventory Management**: Add, remove, and update stock details.
3. **Supply Chain Tracking**: Monitor shipments and track drugs across the supply chain.
4. **Generate Reports**: Create inventory reports and export them for analysis.

## API Endpoints

- **/api/drugs** - Get a list of drugs
- **/api/drugs/:id** - Get details of a specific drug
- **/api/inventory/add** - Add drug to inventory
- **/api/inventory/update** - Update inventory details
- **/api/shipment/track** - Track shipment by ID

## Future Scope

- **Integration with Barcode Scanning**: To automate inventory tracking and management.
- **Blockchain for Enhanced Security**: Improve traceability and prevent counterfeit drugs.
- **Advanced Analytics with Machine Learning**: Predict demand and optimize stock levels.

## Contributing

Contributions are welcome! Please fork the repository and make a pull request. For major changes, open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

---
