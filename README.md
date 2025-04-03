🛒 Shopping App (Kotlin)

A simple and modern Shopping App built with **Kotlin** and **Firebase**, featuring product listings, address selection, and a smooth checkout process.

📌 Features
- 📋 View a list of products with names, prices, and details.
- 📦 Add and manage delivery addresses.
- 🎯 Select an address before proceeding to payment.
- ✅ Order confirmation message upon checkout.
- 🔥 Attractive and user-friendly UI with **Material Design**.

📷 Screenshots
| Home Page | Address Selection | Payment Page |
|-----------|------------------|--------------|
| ![Home Page](screenshots/home.png) | ![Address](screenshots/address.png) | ![Payment](screenshots/payment.png) |

🚀 Installation Guide
1. Clone the repository
   ```sh
   git clone https://github.com/yourusername/ShoppingApp-Kotlin.git
   cd ShoppingApp-Kotlin
Open in Android Studio

Ensure you have the latest Android Studio & Kotlin SDK installed.

Open the project in Android Studio and wait for Gradle sync.

Add Firebase Configuration

Create a Firebase project at Firebase Console.

Download google-services.json and place it inside app/ directory.

Run the App

Click the Run ▶️ button in Android Studio.

📂 Project Structure
swift
 
Edit
ShoppingApp-Kotlin/
│── app/
│   ├── src/main/java/com/example/shoppingappkotlin/
│   │   ├── ui/activities/ (All Activities)
│   │   ├── ui/adapters/ (RecyclerView Adapters)
│   │   ├── models/ (Data Models)
│   │── res/layout/ (XML UI files)
│── build.gradle
│── README.md
🛠 Technologies Used
Kotlin for backend logic.

XML for UI design.

Firebase Firestore for storing user data.

Material Design for UI components.

💡 Contribution
Fork the repository 🍴

Create a new branch

sh
 
Edit
git checkout -b feature-branch
Commit changes ✅

sh

Edit
git commit -m "Added new feature"
Push to GitHub 🚀

sh
Edit
git push origin feature-branch


