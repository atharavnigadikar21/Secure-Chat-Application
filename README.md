# Secure-Chat-Application
The Secure Chat Application is a real-time messaging platform that ensures confidential, end-to-end encrypted communication between users. Designed with security and privacy as top priorities, it allows users to send and receive text messages, files, and media safely without the risk of interception.
🎯 Key Features:
💬 Real-Time Messaging using  Firebase.

🔐 End-to-End Encryption (E2EE) for private messages.

🧾 Message Delivery Status (Sent, Delivered, Read).

📁 Secure File Sharing (images, documents).

🧑‍🤝‍🧑 User Authentication & Authorization using Firebase Predefined Functions..
🛠️ Tech Stack:

Layer	Technologies Used
Frontend	 Flutter / Android (Java/Kotlin)
Database	Firebase Realtime DB

Firebase Cloud Messaging (FCM)
Firebase Hosting
🔒 Security Implementation:
End-to-End Encryption (E2EE):

Messages are encrypted on the sender's device and decrypted only on the receiver’s device using AES or RSA keys.

Private keys are stored locally, not on the server.

Secure Password Storage:

Passwords are hashed using BCrypt before storing in the database.

HTTPS Only:

All communication happens over secure HTTPS to prevent MITM attacks.

JWT Tokens:

Used for secure user sessions. Each request is authenticated and authorized via tokens.

Input Validation & Sanitization:

Prevents injection attacks like XSS and SQL Injection.

🎯 Real-World Use Case:
This application is ideal for users or organizations that require confidential messaging, such as:

Startups and businesses sharing sensitive project details.

Student groups sharing academic material securely.

Individuals looking for privacy-focused alternatives to mainstream chat apps.

📽️ Demo:
Click here to watch the demo video (https://drive.google.com/file/d/1LRvPSwVH6UwJq_vQDEVgbyfYoOihe_Mc/view?usp=drive_link)

For Code base Cheak My another Git Hub Profile [http://github.com/flutteratharav/rakshakchatapp]

✅ Future Scope:
Voice & Video Calling with Encryption

Multi-device Sync with Secure Backup

AI-Powered Spam Filtering

Blockchain-based Message Verification
