# Canteen Pro 🍽️👨‍🍳

An advanced canteen management system developed for the SLIIT 3rd Year 2nd Semester ITPM module. Canteen Pro streamlines canteen operations, offering a seamless experience for administrators, staff, and students.

npm install
npm run dev

## 🚀 Features

- User authentication & role-based access
- Canteen directory and details management
- Menu creation and updates
- Order placement and tracking
- Cart and checkout system
- Staff and admin dashboards
- Announcements and notifications
- Responsive, modern UI (React + Tailwind CSS)
- RESTful API backend (Node.js, Express, MongoDB)
- End-to-end testing with Playwright

## 📦 Project Structure

```
canteen-pro/
	client/   # Frontend (React, Vite, Tailwind)
	server/   # Backend (Node.js, Express, MongoDB)
```

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/RAVINDUTRP/Canteen-Pro.git
cd Canteen-Pro
```

### 2. Install Dependencies

```bash
npm install
cd server && npm install
cd ../client && npm install
```

### 3. Configure Environment

- Copy `server/.env.example` to `server/.env` and update with your settings (MongoDB URI, JWT secret, etc).

### 4. Run the Application

- **Full stack (recommended):**
	```bash
	npm run dev
	```
	- Frontend: [http://localhost:3000](http://localhost:3000)
	- Backend API: [http://localhost:5000](http://localhost:5000)

- **Individually:**
	- Backend: `cd server && npm run dev`
	- Frontend: `cd client && npm run dev`

## 🧪 Testing

- Install Playwright browsers:
	```bash
	npm run test:e2e:install
	```
- Run all E2E tests:
	```bash
	npm run test:e2e
	```

## 🤝 Contributing

1. Fork this repository
2. Create a new feature branch
3. Commit your changes
4. Open a pull request

Please follow the existing code style and folder structure.

## 📄 License

This project is licensed under the MIT License.

---

## Notes
- Make sure MongoDB (or your chosen database) is running and accessible.
- Update environment variables as needed for your local setup.
- For any issues, check logs in the terminal for both client and server folders.

---

## Playwright E2E Testing

### 1. Install Playwright Browser
Run once after installing dependencies:

```bash
npm run test:e2e:install
```

### 2. Run E2E Tests

```bash
npm run test:e2e
```

### 3. Useful Variants

```bash
npm run test:e2e:headed
npm run test:e2e:ui
```

Notes:
- Tests are in `client/tests`.
- Playwright starts the Vite client automatically on port `3000`.

---

## Contributing
- Fork the repo, create a feature branch, and submit a pull request.
- Follow the folder structure and code style for consistency.

---

## License
MIT
