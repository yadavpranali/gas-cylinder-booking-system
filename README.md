# Gas Booking Application

An online cylinder gas booking system that enables customers to book and manage gas deliveries conveniently.

## 📋 Overview

This Gas Booking Application is a web-based platform that allows customers to book gas cylinders online, track deliveries, manage their accounts, and make payments. It streamlines the gas distribution process for both customers and service providers.

## 🛠️ Tech Stack

- **Python** - Backend logic and server processing
- **Django/Flask** - Web framework
- **HTML** - Frontend markup
- **CSS** - Styling and layout

## 📊 Project Statistics

- Python: ~24.1 KB
- HTML: ~19.0 KB

## 🎯 Features

- 📱 User Registration & Login
- 🛒 Gas Cylinder Booking
- 📍 Delivery Address Management
- 💳 Payment Integration
- 📊 Order History & Tracking
- 🔔 Delivery Notifications
- ⭐ User Reviews & Ratings
- 🏢 Admin Dashboard
- 📞 Customer Support
- 📈 Sales Analytics

## 🚀 Getting Started

### Prerequisites
- Python 3.6+
- pip
- Virtual environment

### Installation

```bash
# Clone the repository
git clone https://github.com/yadavpranali/GasBooking_Application.git
cd GasBooking_Application

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure database
python manage.py migrate

# Create admin account
python manage.py createsuperuser

# Run development server
python manage.py runserver
```

## 📁 Project Structure

```
GasBooking_Application/
├── manage.py
├── requirements.txt
├── gasbooking/          # Main project
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── bookings/            # Booking management
├── users/               # User management
├── payments/            # Payment processing
├── templates/           # HTML templates
└── static/              # CSS, JS, images
```

## 🔧 Key Features Explained

### Booking System
- Users select cylinder type and delivery location
- Choose preferred delivery date and time
- Real-time availability checking

### Payment Gateway
- Multiple payment options (Credit/Debit/UPI)
- Secure transaction processing
- Payment confirmation and receipts

### Order Tracking
- Real-time delivery status updates
- SMS/Email notifications
- Delivery agent contact details

### Admin Dashboard
- Order management
- Delivery scheduling
- Customer analytics
- Revenue reports

## 📝 Usage Guide

### For Customers

1. **Register/Login** - Create account and log in
2. **Book Gas** - Select cylinder type and delivery location
3. **Track Order** - Monitor delivery status in real-time
4. **Manage Account** - Update profile and preferences

### For Admin

1. Access `/admin` with superuser credentials
2. Manage bookings, users, and payments
3. Schedule deliveries
4. View analytics and reports

## 🛡️ Security Features

- ✅ SSL/HTTPS encryption
- ✅ Password hashing
- ✅ CSRF protection
- ✅ SQL injection prevention
- ✅ Input validation
- ✅ Secure payment processing

## 💳 Payment Integration

Configure payment gateway in `settings.py`:
- Stripe / Razorpay / PayPal
- Add API keys and credentials

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

## 📧 Support

For issues or feature requests, create a GitHub issue.

## 📄 License

See LICENSE file for details.

---

**Convenient Gas Booking at Your Fingertips! 🔥**
