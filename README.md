# SecurePass — Password Strength & Breach Checker

A password security analysis tool built with React, TypeScript, and n8n.

## Features

- Password strength scoring (0–100)
- Common password and predictable-pattern detection
- Password complexity analysis
- Breach checking using the Have I Been Pwned Pwned Passwords API
- Security recommendations
- JSON API integration through an n8n webhook

## Tech Stack

- React
- TypeScript
- n8n
- REST API
- Have I Been Pwned Pwned Passwords API

## Architecture

1. User enters a password in the frontend.
2. The frontend sends a POST request to the n8n webhook.
3. n8n calculates password strength and checks for known breach matches.
4. The API returns the analysis and recommendations.

## Security Notes

- Never use a real password for testing.
- Passwords should not be stored or logged.
- A password not found in breach data is not guaranteed to be safe.
- This project is for educational purposes and is not a substitute for a professional security audit.

## Project Status

Personal project — testing and development.

## Author

Tanish Ahuja
