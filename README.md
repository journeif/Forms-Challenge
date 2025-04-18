# Forms Homework 📝

A simple full-stack application demonstrating form validation, unit testing, and data persistence using Docker, React, and MongoDB.

## 🛠 Tech Stack

- **Frontend:** React, Vite
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Containerization:** Docker & Docker Compose
- **Testing:** @testing-library/react
- **Linting:** ESLint (optional)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/forms-homework.git
cd forms-homework
2. Set Up .env
Create a .env file in the root (if needed for backend secrets).

touch .env
Add environment variables as needed, e.g.,

PORT=5000
MONGO_URL=mongodb://mongo:27017/registration
3. Run the App with Docker
Make sure Docker is running, then:

docker-compose up --build
Backend will run at: http://localhost:5000
Frontend will run at: http://localhost:5173 (or whatever your React port is)
🧪 Running Unit Tests

npm test
Or with coverage:

npm test -- --coverage
Tests are written using @testing-library/react for React components.

🧾 Features

✅ Form validation (required fields, email format, phone number length)
✅ Real-time error messages
✅ Data submission to backend
✅ Data stored in MongoDB
✅ Dockerized frontend, backend, and database
✅ Unit tests for form behavior


### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
