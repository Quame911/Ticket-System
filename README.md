# TicketHub - Event Ticketing System

A modern web-based ticketing system that allows users to browse events, purchase tickets, and receive QR-coded tickets via email.

## Features

- User registration and authentication
- Browse and search events by category
- Secure payment processing with Paystack
- QR code ticket generation
- Email ticket delivery
- Mobile-responsive design
- Admin dashboard for event management

## Tech Stack

- Frontend: HTML5, CSS3, JavaScript (Vanilla)
- Database: MySQL
- Payment Integration: Paystack
- Email Service: SendGrid (recommended)
- QR Code Generation: qrcode.js

## Project Structure

```
tickethub/
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── images/
├── database/
│   └── schema.sql
├── index.html
└── README.md
```

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tickethub.git
   cd tickethub
   ```

2. Database Setup:
   - Create a MySQL database
   - Import the schema from `database/schema.sql`
   ```bash
   mysql -u your_username -p your_database_name < database/schema.sql
   ```

3. Configuration:
   - Update the database connection details in your configuration
   - Set up your Paystack API keys
   - Configure your email service (SendGrid) API keys

4. Running the Project:
   - Open `index.html` in your web browser for development
   - For production, deploy to a web server

## Required API Keys

You'll need to obtain API keys for:
- Paystack (Payment processing)
- SendGrid (Email service)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Your Name - your.quametempest1327@gmail.com
Project Link: https://github.com/Quame911/tickethub 
