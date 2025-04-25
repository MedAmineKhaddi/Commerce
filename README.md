# PrjCommerce

PrjCommerce is an e-commerce web application built with Django and PostgreSQL. This project provides a foundation for building scalable and secure online stores.

## Features

- User authentication and registration
- Product catalog management
- Shopping cart functionality
- Order processing
- PostgreSQL database integration
- Secure password validation
- SSL database connection

## Project Structure

```
PrjCommerce/
├── PrjCommerce/           # Django project settings and configuration
├── Lib/                   # Virtual environment libraries
├── Scripts/               # Virtual environment scripts
├── requirement.txt        # Python dependencies
├── CACHEDIR.TAG           # Cache directory tag (ignored by Git)
├── pyvenv.cfg             # Virtual environment config
└── README.md              # Project documentation
```

## Getting Started

### Prerequisites

- Python 3.8+
- PostgreSQL database
- pip

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MedAmineKhaddi/Commerce.git
   cd Commerce
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirement.txt
   ```

4. **Configure the database:**
   - Update the `DATABASES` section in `PrjCommerce/PrjCommerce/settings.py` with your PostgreSQL credentials.

5. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the app:**
   Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

## Usage

- Register a new user or log in.
- Browse products, add them to your cart, and place orders.
- Manage your profile and view order history.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For questions or support, open an issue or contact [MedAmineKhaddi](https://github.com/MedAmineKhaddi).
