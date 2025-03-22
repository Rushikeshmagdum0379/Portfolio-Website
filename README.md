**React Portfolio**
This is a React-based Portfolio Website showcasing projects and skills. The website is built using Vite for a fast development experience and integrates Firebase for additional functionality.

**Features**
Modern UI/UX: Styled with Poppins font for a clean and professional look.

**React & Vite:** Uses the latest version of React and Vite for optimized performance.

**Firebase Integration:** Includes Firebase for backend support (authentication, database, etc.).
**
**SEO Optimized:** **Metadata and OpenGraph tags included for better search engine visibility.

**Project Structure**


/react-portfolio  
│-- public/  
│-- src/  
│   │-- components/  
│   │-- assets/  
│   │-- pages/  
│   └── main.jsx  
│-- index.html  
│-- package.json  
│-- vite.config.js  
│-- README.md  
**
**Installation
Prerequisites****
Node.js (v16+ recommended)

npm (v8+ recommended)

**Steps**
1 : Clone the repository


git clone https://github.com/your-username/react-portfolio.git  
cd react-portfolio  

2: Install dependencies
npm install  
Run in development mode

3: npm run dev  
Build for production

4 : npm run build  
Preview the build

5 :npm run preview  

**Technologies Used**
React ^18.0.0

Vite ^2.9.9

Firebase ^11.1.0

React Icons for UI elements

React Markdown for content formatting

**Configuration**

Modify the vite.config.js file to adjust Vite settings:

javascript

import { defineConfig } from 'vite'  
import react from '@vitejs/plugin-react'  

export default defineConfig({  
  plugins: [react()],  
  publicDir: 'public',  
})  
Project Done By Rushikesh Magdum
