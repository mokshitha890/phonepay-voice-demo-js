# PhonePe-Style Voice Payment Notification

This project is a **voice-based payment confirmation system**, inspired by **PhonePe**. It dynamically constructs and plays audio messages for transaction confirmations, providing a seamless user experience similar to real-world digital payment applications.

## 🔹 Features
- Accepts user input for the transaction amount
- Breaks down numbers into thousands, hundreds, tens, and ones
- Dynamically selects and plays pre-recorded audio clips for each number
- Ensures smooth audio playback for a natural-sounding notification

## 🔹 How It Works
1. The user enters an amount (0–9999).
2. The script breaks down the number and maps it to corresponding audio files.
3. The system plays the clips in sequence to form a complete notification, e.g.:
   **"You received 2,350 to your bank account."**

## 🔹 Tech Stack
- **JavaScript** – Handles number processing and audio sequencing
- **HTML & CSS** – Provides a simple, responsive UI
- **Pre-recorded audio clips** – Used for dynamic voice playback

## 🔹 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/mokshitha890/phonepay-voice-demo-js
   cd phonepe-voice-notification
   ```
2. Open `index.html` in a browser.
3. Enter an amount and press **Play** to hear the voice notification.

## 🔹 Demo
[Demo Link](https://phonepay-voice.netlify.app/)


## 🔹 Contributing
Feel free to **fork** this repository, submit issues, or create pull requests. Contributions are welcome!

## 🔹 License
This project is licensed under the **MIT License**.

