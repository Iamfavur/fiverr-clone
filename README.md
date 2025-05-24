# Fiverr Clone

A full-featured Fiverr marketplace clone built with TypeScript. This project emulates the core functionalities of the Fiverr platform, allowing users to buy and sell freelance services in a modern, scalable, and user-friendly web application.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Features

- **User Authentication**: Register, login, and manage user profiles.
- **Service Listings (Gigs)**: Create, edit, browse, and search for freelance gigs.
- **Order Management**: Place and manage orders, including order tracking and status updates.
- **Messaging System**: Communicate between buyers and sellers.
- **Reviews & Ratings**: Leave and view feedback for services.
- **Responsive UI**: Mobile-friendly design.
- **Admin Panel**: Manage users, gigs, orders, and disputes (if implemented).

---

## Tech Stack

- **Frontend**: TypeScript, Next.js
- **Backend**: Node.js, Express.js 
- **Database**: MongoDB 
- **Styling**: Tailwind CSS 
- **Authentication**: JWT, 
- **Other Tools**: 
  - Redux and Context API for state management
  - RESTful APIs
  - Form validation libraries (Formik)

---

## Project Structure

```
fiverr-clone/
├── client/               # Frontend source code
│   ├── src/
│   └── public/
├── server/               # Backend source code
│   ├── src/
│   └── config/
├── shared/               # Shared types and utilities (if monorepo)
├── package.json
├── README.md
└── ...
```
> _Note: Your actual structure may vary; adjust to match your implementation._

---

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn
- MongoDB running locally or a connection string to a cloud provider

### Installation

#### 1. Clone the repository
```bash
git clone https://github.com/Iamfavur/fiverr-clone.git
cd fiverr-clone
```

#### 2. Install dependencies

- **Frontend:**
  ```bash
  cd client
  npm install
  ```

- **Backend:**
  ```bash
  cd ../server
  npm install
  ```

#### 3. Configure environment variables

Create a `.env` file in the `server` directory with your configuration:

```
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret
CLIENT_URL=http://localhost:3000
```

Adjust as needed for your setup.

#### 4. Run the application

- **Backend:**
  ```bash
  npm run dev
  ```

- **Frontend:**
  ```bash
  cd ../client
  npm start
  ```

The app should now be running at [http://localhost:3000](http://localhost:3000) (frontend) and [http://localhost:5000](http://localhost:5000) (backend).

---

## Usage

- **Register** as a new user or **log in** to your account.
- **Browse gigs** or **post your own**.
- **Order services**, communicate with freelancers, and manage your orders.
- **Leave reviews** after order completion.

> _For more details, refer to the documentation or code comments._

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Inspired by [Fiverr](https://www.fiverr.com/)
- [Nextjs](https://nextjs.org/), [TypeScript](https://www.typescriptlang.org/), [Node.js](https://nodejs.org/)
- Thanks to all open-source contributors!

---

> _For questions or support, please open an issue or contact the maintainer._
