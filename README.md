n8n OTP Auth

A secure OTP (One-Time Password) authentication system integrated with n8n workflow automation. This project enables email or mobile-based OTP verification for user authentication, login validation, and automated workflow triggering.

Features
OTP generation and verification
Email and mobile authentication support
Secure login validation
Integration with n8n workflows
API-based authentication handling
Easy deployment and customization
Modern full-stack architecture
Tech Stack
Frontend: React.js / HTML / CSS / JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Automation: n8n
Authentication: OTP-based verification
Installation
git clone https://github.com/GaganReddy03460/n8n-otp-auth.git
cd n8n-otp-auth
npm install
Run the Project
npm start
Environment Variables

Create a .env file and configure:

MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
OTP_EXPIRY=5m
Usage
Register or log in using email/mobile.
Receive OTP for verification.
Verify OTP to authenticate access.
Trigger automated workflows through n8n integration.
Future Enhancements
Two-factor authentication (2FA)
OAuth login support
Rate limiting and security improvements
Docker deployment support
Admin dashboard
License

This project is licensed under the MIT License.# Mobile-with-auth-and-n8n
Secure OTP Authentication System for n8n with email/mobile verification, workflow automation, and user authentication integration using modern full-stack technologies.
