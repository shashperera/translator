# Translator App

The Translator App is a web application that allows users to translate text from one language to another using various translation services. It's built with React, TypeScript, Firebase, and integrates Figma designs for a seamless user experience.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Firebase Setup](#firebase-setup)
- [Contributing](#contributing)
- [License](#license)

## Features

- Translate text from one language to another.
- User authentication (optional).
- Integration with Firebase for data storage and authentication.
- Responsive design based on Figma designs.
- Easy-to-use interface.

## Demo

[Link to Design demo](https://www.figma.com/proto/cfNVAFO1B5ejEVeJdONFpW/Translator?type=design&node-id=1-1439&t=X1wl4Iwx8cpLYvFo-1&scaling=min-zoom&page-id=0%3A1&mode=design)

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/translator-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd translator-app
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

To start the development server, run:

```bash
npm start
```

Visit `http://localhost:3000` in your web browser to access the application.

## Firebase Setup

Before running the application, you need to set up Firebase for authentication and data storage. Follow these steps:

1. Create a Firebase project on the [Firebase Console](https://console.firebase.google.com/).
2. Set up Firebase Authentication if you want to enable user authentication.
3. Set up Firestore database for storing translation data.
4. Obtain Firebase configuration settings (apiKey, authDomain, projectId, etc.) to connect your app to Firebase.
5. Add the Firebase configuration to your app's environment variables or configuration file.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/improvement`).
5. Create a new Pull Request.

### Contributors

- [Prabodha Lenora](https://github.com/prabolenora)
- [Sanduni Perera](https://github.com/shashperera)

## License

This project is licensed under the [MIT License](LICENSE).
