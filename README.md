🤖 WhatsApp Bot for Rural Businesses
    A Python-based WhatsApp automation bot designed to assist rural businesses in managing customer interactions, registrations, and basic inventory via WhatsApp. 
    Built using Flask, Twilio API, and Excel/SQLite, the bot enables business owners to operate with minimal tech knowledge through a familiar chat interface.

🌟 Key Features
📝 New customer/business registration via WhatsApp

📄 Record keeping using Excel or SQLite

📆 Date-wise logging and response tracking

🧾 Automated response to keywords (e.g., "Register", "Help")

📤 Daily interaction handling with customizable logic

🌐 Built with Flask – lightweight and deployable on any server

🛠️ Tech Stack
    Python

    Flask

    Twilio WhatsApp API

    openpyxl / SQLite (for storing data)

    datetime, re, os (for logic, logging & formatting)
    
-->Folder Structure
/whatsapp-bot
├── app.py                # Flask server with webhook logic
├── templates/            # Optional: for admin interfaces
├── users.xlsx            # Excel file to store user data
├── requirements.txt      # Project dependencies
