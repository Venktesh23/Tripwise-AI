# TripWise AI

**TripWise AI** is a cutting-edge, full-stack trip planning application designed to make travel planning smart, efficient, and personalized. By integrating React, Gemini AI, Firebase, and TailwindCSS, TripWise AI delivers a seamless user experience with intelligent itinerary recommendations and a sleek, responsive design.

## Features

- **AI-Driven Itineraries**: Utilizes Gemini AI to create customized travel plans based on user preferences such as destination, duration, and budget.
- **Real-Time Updates**: Employs Firebase for real-time data management, ensuring that travel plans are always current.
- **Responsive Design**: Built with TailwindCSS for an intuitive and adaptive user interface across all devices.
- **Secure Authentication**: Implements Firebase Authentication for safe and reliable user login and profile management.

## Tech Stack

- **Frontend**: React.js, TailwindCSS
- **Backend**: Firebase (Functions & Firestore)
- **AI Integration**: Gemini AI for generating and optimizing travel itineraries
- **Authentication**: Firebase Authentication

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/tripwise-ai.git
   cd tripwise-ai
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following:
   ```bash
   FIREBASE_API_KEY=your_firebase_api_key
   FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   FIREBASE_PROJECT_ID=your_firebase_project_id
   FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   FIREBASE_APP_ID=your_firebase_app_id
   GEMINI_API_KEY=your_gemini_api_key
   ```

4. **Run the application**:
   ```bash
   npm run dev
   ```

5. **Access the application**:
   Open your browser and navigate to `http://localhost:3000`.

## Usage

1. **Sign Up/Login**: Securely create an account or log in to access personalized features.
2. **Plan a Trip**: Input your travel details and preferences to generate a tailored itinerary.
3. **Save & Share**: Save your trip plans for future reference or share them with others.

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

