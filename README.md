# Redux Project with RTK Query and Redux Toolkit

This project demonstrates a simple yet comprehensive setup of Redux using the **Redux Toolkit** and **RTK Query** in a React application. Built with **Vite** for a fast and efficient development experience.

## Features
- State management using Redux Toolkit
- API calls handled using RTK Query
- Fast Refresh support via Vite
- Linting configured with ESLint

## Tech Stack
- React
- Redux Toolkit
- RTK Query
- Vite
- ESLint

## Getting Started

### Prerequisites
- Node.js (v16+)
- npm or yarn

### Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/CodeBoyD7/redux-project.git
cd redux-project
npm install
```

### Running the Development Server
To start the development server, run:

```bash
npm run dev
```

The app will be running at **http://localhost:5173**.

## Project Structure
```
.
├── RTK Query       # API service setup using RTK Query
├── Redux Toolkit   # State management using Redux Toolkit
├── public          # Static assets
├── src             # Source code
│   ├── components  # Reusable UI components
│   ├── features    # Redux slices and RTK Query services
│   ├── pages       # Application pages
│   └── store       # Redux store configuration
├── .gitignore      # Files to ignore in version control
├── README.md       # Project documentation
├── package.json    # Dependencies and scripts
├── vite.config.js  # Vite configuration file
└── index.html      # Main HTML file
```

## ESLint Configuration
The project uses ESLint for consistent code formatting and error checking. To run the linter, use:

```bash
npm run lint
```

## Building for Production
To build the project for production, run:

```bash
npm run build
```

The production-ready files will be in the **dist** folder.

## Contributing
Feel free to fork this project and submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License.

