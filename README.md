# Freznel AI — Model Selector

> A modern AI model discovery and comparison platform built as part of the **Freznel AI Assessment**.

Freznel AI Model Selector helps users discover, search, filter, sort, and explore AI models through a clean and intuitive interface. The application is designed to make finding the right AI model faster by organizing model information into a structured and user-friendly experience.

---

## 🚀 Overview

With the rapid growth of AI models and providers, choosing the right model for a particular task can become difficult.

**Freznel AI — Model Selector** addresses this problem by providing a centralized interface where users can:

* 🔎 Search for AI models
* 🧠 Explore available models
* 🏷️ Filter models based on relevant attributes
* ↕️ Sort model results
* 📊 Compare model information
* 🔐 Manage authentication
* ⚡ Browse models through a responsive interface
* 💾 Work with Firebase-backed application data

The project focuses on making AI model discovery **simple, fast, and practical**.

---
<img width="1913" height="892" alt="image" src="https://github.com/user-attachments/assets/05ab0886-d11b-48a6-a49b-7ea4752f6a28" />


## ✨ Features

### 🔍 Model Search

Search through available AI models using a simple and responsive search interface.

### 🎯 Filtering

Narrow down model results using different filtering options to quickly find relevant models.

### ↕️ Sorting

Sort model results according to supported model attributes, making large result sets easier to navigate.

### 🧠 Model Information

View structured information about individual AI models in an organized interface.

### 🔐 Authentication

The application includes authentication-related functionality for managing user access.

### ⚡ Responsive UI

Designed to provide a smooth experience across different screen sizes.

### ☁️ Firebase Integration

Firebase is used as part of the application's backend infrastructure, including Firestore configuration and application data management.

---

## 🛠️ Tech Stack

| Technology     | Purpose                       |
| -------------- | ----------------------------- |
| **React**      | Frontend application          |
| **TypeScript** | Type-safe development         |
| **Vite**       | Development and build tooling |
| **Firebase**   | Backend services              |
| **Firestore**  | Data storage                  |
| **ESLint**     | Code quality and linting      |
| **CSS**        | Styling and responsive UI     |

---

## 📁 Project Structure

```text
Binaire-FreznelAI-Assessment/
│
├── public/
│
├── src/
│   ├── api/          # API and data access
│   ├── auth/         # Authentication logic
│   ├── components/   # Reusable UI components
│   ├── filters/      # Model filtering functionality
│   ├── hooks/        # Custom React hooks
│   ├── models/       # Model-related logic/data
│   ├── offline/      # Offline-related functionality
│   ├── pages/        # Application pages
│   ├── search/       # Search functionality
│   ├── sorting/      # Sorting functionality
│   ├── styles/       # Styling
│   ├── types/        # TypeScript types
│   └── utils/        # Utility functions
│
├── firebase.json
├── firestore.rules
├── eslint.config.js
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Satyam7295/Binaire-FreznelAI-Assessment.git
```

### 2. Navigate into the project

```bash
cd Binaire-FreznelAI-Assessment
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure Firebase

Create/configure your Firebase project and add the required Firebase configuration to the project.

Make sure the required environment variables are available before running the application.

Example:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

> **Important:** Never commit private credentials, service-account keys, or other secrets to GitHub.

### 5. Start the development server

```bash
npm run dev
```

The application will be available at the local development URL provided by Vite.

---

## 🏗️ Build for Production

Create a production build using:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

## 🧪 Code Quality

Run ESLint with:

```bash
npm run lint
```

This helps maintain consistent and reliable code throughout the project.

---

## 🔄 Application Flow

```text
                    ┌───────────────────┐
                    │      User         │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │   Model Selector  │
                    │        UI         │
                    └─────────┬─────────┘
                              │
                 ┌────────────┼────────────┐
                 ▼            ▼            ▼
             Search       Filters       Sorting
                 │            │            │
                 └────────────┼────────────┘
                              ▼
                    ┌───────────────────┐
                    │   Model Data/API  │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │ Firebase / Data   │
                    │     Layer         │
                    └───────────────────┘
```

---

## 🎯 Goals of the Project

The project was developed to demonstrate practical skills in:

* Frontend application development
* React and TypeScript
* API/data integration
* Search implementation
* Filtering and sorting
* Authentication
* Firebase integration
* Component-based architecture
* Responsive UI development
* Clean and maintainable project structure

---

## 🔮 Future Improvements

Possible future enhancements include:

* ⭐ Model bookmarking and favourites
* 📊 Side-by-side model comparison
* 📈 Model performance analytics
* 🧮 Advanced model ranking
* 💰 Cost comparison between models
* ⚡ Improved caching and offline support
* 🌙 Dark/light theme customization
* 👤 User-specific model recommendations
* 🤖 AI-powered model recommendations
* 📱 Further mobile optimization

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/your-feature
```

3. Commit your changes

```bash
git commit -m "Add your feature"
```

4. Push the branch

```bash
git push origin feature/your-feature
```

5. Open a Pull Request

---

## 📄 License

This project was created as part of the **Freznel AI Assessment**.

Please refer to the repository and assessment requirements for applicable usage and licensing information.

---

## 👨‍💻 Author

**Satyam Sachan**

GitHub:
https://github.com/Satyam7295

---

## ⭐ Acknowledgements

Built for the **Freznel AI Model Selector Assessment**.

If you find the project useful or interesting, consider giving the repository a ⭐.
