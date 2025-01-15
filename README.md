
# XORA (SaaS Landing Page)

XORA is a modern, responsive SaaS landing page designed to showcase and promote software solutions effectively. It features smooth animations, scroll-based interactions, and dynamic counters for engaging user experiences.

---

## Features

### Core Functionalities
- **Smooth Scrolling**: Seamless navigation with scroll-based animations using `react-scroll`.
- **Animated Counters**: Dynamic numerical displays powered by `react-countup`.
- **Collapsible Sections**: Interactive and collapsible content using `react-slidedown`.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices using Tailwind CSS.

### Development Tools
- **Class Management**: Simplified class management with `clsx` for dynamic styling.
- **Prettier Integration**: Ensures consistent code formatting across the project.

---

## Technologies Used

### Frontend Libraries
- **React.js**: Framework for building the user interface.
- **React DOM**: DOM-specific methods for React.
- **react-scroll**: For smooth scrolling and animations.
- **react-slidedown**: Collapsible animations for dynamic sections.
- **react-countup**: Animated counters for engaging visual elements.
- **clsx**: Utility for conditional class name handling.

### Development Tools
- **Vite**: Fast development and build tool.
- **Tailwind CSS**: Utility-first CSS framework for responsive design.
- **ESLint**: Linter for ensuring code quality and adherence to standards.
- **PostCSS & Autoprefixer**: CSS processing and cross-browser compatibility.

---

## Prerequisites

Before starting, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 16 or higher recommended)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

---

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SKele10/Xora.git
   cd xora
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the Development Server**:
   ```bash
   npm run dev
   # or
   yarn dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Project Structure

```
/
|-- public/                 # Static assets (e.g., favicon, images)
|-- src/                    # Source code
|   |-- components/         # Reusable React components
|   |-- pages/              # Page-level components
|   |-- App.jsx             # Main application file
|-- index.html              # Main HTML file
|-- package.json            # Project dependencies and metadata
|-- tailwind.config.js      # Tailwind CSS configuration
|-- vite.config.js          # Vite configuration
```

---

## Deployment

1. **Build for Production**:
   ```bash
   npm run build
   ```

2. **Serve the Production Build**:
   Deploy the `dist` folder using platforms such as:
   - [Netlify](https://www.netlify.com/)
   - [Vercel](https://vercel.com/)
   - [AWS S3](https://aws.amazon.com/s3/)

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
