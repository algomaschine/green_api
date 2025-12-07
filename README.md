# WhatsApp Business API Dashboard

A modern web interface for testing and interacting with Green-API (WhatsApp Business API). This dashboard provides a sleek interface to test API endpoints without writing code.

## Features

- **Four API Methods Implemented**:
  1. `GetSettings` - Get current instance settings
  2. `GetStateInstance` - Check instance authorization state
  3. `SendMessage` - Send text messages
  4. `SendFileByUrl` - Send files via URL

- **Modern 2025 Design**:
  - Dark theme with WhatsApp green accents
  - Responsive layout for all screen sizes
  - Smooth animations and transitions
  - Real-time API response logging

- **User-Friendly Interface**:
  - Pre-filled test credentials
  - Auto-formatting of chatId
  - File name extraction from URLs
  - Loading indicators for API calls

## Prerequisites

1. **Green-API Account**: You need an active Green-API account
2. **Instance Credentials**: 
   - Instance ID (provided: `1103411672`)
   - API Token (provided: `1da8f9794eeb4d52b424093265b692263c30b30616d84b3792`)
3. **Internet Connection**: For API calls and loading Font Awesome icons

## How to Use

### Running Locally (Easiest Method)

1. **Save the HTML file**:
   - Copy the entire HTML code
   - Save as `whatsapp-api-dashboard.html` on your computer

2. **Open in browser**:
   - Double-click the HTML file
   - It opens in your default browser

3. **Make API calls**:
   - The credentials are pre-filled
   - Click buttons to test API methods
   - View responses in the right panel

### Uploading to a Web Server

#### Method 1: Using Shared Hosting (cPanel)

1. **Access your hosting control panel** (cPanel)
2. **Navigate to File Manager**
3. **Upload the HTML file** to your public directory (usually `public_html` or `www`)
4. **Access the dashboard** at: `https://yourdomain.com/whatsapp-api-dashboard.html`

#### Method 2: Using VPS/Cloud Server

1. **Upload via SFTP/SCP**:
   ```bash
   scp whatsapp-api-dashboard.html user@yourserver:/var/www/html/
