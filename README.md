# Educational Chatbot

This project is an educational chatbot that connects to Firebase and Dialogflow. It provides an interactive interface for users to engage with the chatbot, which can answer questions and provide information based on user input.

## Project Structure

```
educational-chatbot
├── public
│   ├── index.html          # Main HTML entry point
│   └── styles
│       └── main.css       # Styles for the application
├── src
│   ├── components
│   │   └── Chatbot.tsx    # Chatbot component
│   ├── firebase
│   │   └── firebaseConfig.ts # Firebase configuration
│   ├── services
│   │   └── dialogflowService.ts # Dialogflow service functions
│   ├── App.tsx            # Main application component
│   └── index.tsx          # Entry point for the React application
├── package.json            # npm configuration file
├── tsconfig.json           # TypeScript configuration file
├── vite.config.ts          # Vite configuration file
└── README.md               # Project documentation
```

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd educational-chatbot
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Firebase:**
   - Create a Firebase project and obtain your configuration details.
   - Update the `src/firebase/firebaseConfig.ts` file with your Firebase credentials.

4. **Run the application:**
   ```bash
   npm run dev
   ```

5. **Open your browser:**
   - Navigate to `http://localhost:3000` to interact with the chatbot.

## Usage

- Type your questions in the chatbot interface and receive responses powered by Dialogflow.
- The chatbot is designed to assist with educational queries and provide relevant information.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.#   N o v a T u t o r  
 