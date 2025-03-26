# ✅ To-Do List App

<p align="center">A simple and efficient task management app built with React Native and TypeScript.</p>

---

## 📖 About the Project

**To-Do List App** is a mobile application developed to practice core React Native concepts such as state management, UI composition, and interaction handling. The app allows users to create, remove, and complete tasks with a clean and minimalistic design.

It was built as a learning exercise to reinforce knowledge in functional components, hooks, typing with TypeScript, and component reusability.

---

## 🚀 Technologies Used

- **React Native 0.64.2**
- **React 17.0.1**
- **TypeScript**
- **React Native Linear Gradient**
- **React Native Vector Icons**
- **Jest** and **React Native Testing Library** (unit testing)

---

## 🧠 Architecture & Technical Decisions

- The app uses a **component-based architecture** to isolate logic and promote reuse.
- State is managed using **React Hooks** (`useState`) within functional components.
- A custom **ItemWrapper** was created to handle task item animations or logic wrappers.
- Icons and gradient effects are handled using **React Native Vector Icons** and **Linear Gradient**, respectively.
- Tests are written using **Jest** and **Testing Library** to validate UI rendering and behavior.
- The project uses **TypeScript** to ensure type safety and better IDE support.
- The UI is responsive and optimized for both Android and iOS.

---

## 📦 Features

- 📌 Task count display
- ➕ Add new tasks
- ✅ Mark and unmark tasks as complete
- 🗑️ Remove tasks from the list

---

## 🧰 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/to-do-list-app.git
cd to-do-list-app
```

### 2️⃣ Install dependencies
```bash
yarn install
```

### 3️⃣ iOS dependencies (macOS only)
```bash
cd ios && pod install && cd ..
```

### 4️⃣ Run the app
```bash
yarn android     # Run on Android
yarn ios         # Run on iOS
```

---

## 📂 Folder Structure

```
to-do-list-app/
├── android/                  # Android native project
├── ios/                      # iOS native project
├── assets/                   # Fonts and images
├── src/
│   ├── __tests__/            # Component and page tests
│   ├── assets/icons, images  # Static icons and logos
│   ├── components/           # Reusable components (Header, TodoInput, TasksList)
│   └── pages/                # Main screen (Home)
├── App.tsx                   # Entry point
├── app.json, index.js, etc   # Project configs
└── README.md
```

---

## 📄 License

This project is licensed under the MIT License.

---

🚀 Made with ❤️ by [Priscila Oliveira](https://github.com/pripoliveira50/)

