# Two-factor-Auth-simulation
# Password and OTP Verification Script

This Python script demonstrates a basic login authentication system that first validates a password and then sends a One-Time Password (OTP) using the Twilio API for two-step verification.

## Features

- Password authentication
- OTP generation (6-digit)
- OTP sending via Twilio SMS
- Maximum 5 password attempts allowed

## Prerequisites

- Python 3.x
- A [Twilio](https://www.twilio.com/) account
- Twilio credentials (`account_sid`, `auth_token`)
- A verified Twilio phone number
- User's phone number for OTP delivery

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

