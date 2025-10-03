# Calorie-Compass
A modern, single-page web application that uses Google's Gemini API for intelligent meal analysis (text or image) and Firebase Firestore for secure user authentication and real-time meal history tracking.
This project was built by Shamik Byabartta to provide a seamless and smart solution for mindful eating and daily nutritional logging.
# Features
Calorie Compass provides a powerful set of tools to help users manage their diet effectively:
1. **AI-powered meal analysis:** Analyze meals by simply typing a description or uploading an image. The AI provides an approximate nutritional breakdown (calories, protein, carbs, fat).
2. **Real-time meal history:** All analyzed meals are automatically saved to your personal, authenticated history using Firebase Firestore and displayed in real-time.
3. **Intelligent Meal Plan generation:** Based on your stored meal history, the AI can generate a suggested one-day healthy meal plan (requires user verification).
4. **Secure user authentication:** Implements _Email/Password_ sign-up and login using Firebase Authentication.
5. **Mandatory email verification:** Features like _saving history_ and _AI generation_ are locked until the user verifies their _email address_, _ensuring data integrity_ and _account security_.
6. **Responsive design:** A clean, modern UI built with Tailwind CSS that works beautifully across mobile and desktop devices.
7. **Single-file architecture:** The entire application logic (HTML, CSS, JavaScript) is contained within a single index.html file for simplicity and ease of deployment.
# Technology Stack
1. **Frontend:** Pure HTML5, JavaScript (ES6+), CSS (via Tailwind CSS CDN)
2. **Styling:** Tailwind CSS
3. **AI/LLM:** Gemini API (gemini-2.5-flash-preview-05-20 for text and multimodal analysis)
4. Backend/BaaS:
   a. Firebase authentication: For user sign-up, login, and email verification.
   b. Firebase firestore: For persistent, real-time storage of user meal history.
# Usage
1. **Sign up:** Create an account using your email and password.
2. **Verify email:** A verification email will be sent. You must click the link in the email and then use the "I clicked the link" button in the app's modal to refresh your status.
3. **Analyze meal:** Once verified, enter a meal description or upload a photo and click "Analyze Meal". The results will appear and be saved to your history.
4. **Generate plan:** Click "Generate Meal Plan" to get an AI-generated suggestion based on your logged history.
# Contribution
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
# License
1. This project is licensed under the Creator License.
2. Contact Shamik (byabarttashamik@gmail.com) for License Details.

Made with ❤️ by Shamik Byabartta
