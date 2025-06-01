# 🎨 Ecommerce Platform

A modern React frontend for the Ecommerce Platform, built with Vite and styled with Tailwind CSS.

## 🛠️ Tech Stack

- **React 19** - Latest React with modern hooks and features
- **Vite** - Lightning-fast build tool and dev server
- **React Router DOM** - Client-side routing and navigation
- **Tailwind CSS** - Utility-first CSS framework
- **JWT Decode** - JWT token handling
- **Lodash** - Utility library for data manipulation

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation
```bash
npm install
```

### Development
```bash
npm run dev          # Start development server (http://localhost:5173)
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
```

## 📁 Project Structure

```
client/
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/          # Page components
│   ├── hooks/          # Custom React hooks
│   ├── utils/          # Utility functions
│   ├── context/        # React context providers
│   ├── services/       # API service functions
│   └── styles/         # Global styles
├── public/             # Static assets
├── index.html          # HTML template
└── vite.config.js      # Vite configuration
```

## 🎨 Styling

This project uses **Tailwind CSS** for styling with additional form plugins:
- `@tailwindcss/forms` - Better form styling
- Responsive design principles
- Modern UI/UX patterns

## 🔧 Development Tools

### ESLint Configuration
- React-specific linting rules
- React Hooks linting
- React Refresh support

### Vite Features
- Hot Module Replacement (HMR)
- Fast development builds
- Optimized production builds
- Modern JavaScript support

## 🔗 API Integration

The frontend communicates with the backend API for:
- User authentication
- Product management
- Shopping cart operations
- Order processing

## 📱 Responsive Design

The application is fully responsive and optimized for:
- Mobile devices (320px+)
- Tablets (768px+)
- Desktop (1024px+)
- Large screens (1280px+)

## 🧪 Testing

To add testing to this project:
```bash
npm install --save-dev @testing-library/react @testing-library/jest-dom vitest
```

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Static Hosting
The `dist/` folder can be deployed to:
- **Netlify** - Drag and drop deployment
- **Vercel** - Git-based deployment
- **AWS S3** - Static website hosting
- **GitHub Pages** - Free hosting for public repos

### Environment Variables
Create `.env` file for environment-specific configurations:
```env
VITE_API_URL=http://localhost:5000
VITE_APP_NAME=Musa Ecommerce
```

## 💡 Key Features

### Authentication
- JWT-based authentication
- Protected routes
- User session management

### Shopping Experience
- Product browsing and search
- Category filtering
- Shopping cart management
- Checkout process

### User Interface
- Clean, modern design
- Intuitive navigation
- Loading states
- Error handling
- Success notifications

## 🔧 Customization

### Adding New Components
```jsx
// src/components/MyComponent.jsx
import React from 'react';

const MyComponent = ({ prop1, prop2 }) => {
  return (
    <div className="p-4 bg-white rounded-lg shadow">
      {/* Component content */}
    </div>
  );
};

export default MyComponent;
```

### Adding New Pages
```jsx
// src/pages/MyPage.jsx
import React from 'react';

const MyPage = () => {
  return (
    <div className="container mx-auto px-4 py-8">
      {/* Page content */}
    </div>
  );
};

export default MyPage;
```

## 📚 Learn More

- [React Documentation](https://react.dev/)
- [Vite Documentation](https://vitejs.dev/)
- [Tailwind CSS Documentation](https://tailwindcss.com/)
- [React Router Documentation](https://reactrouter.com/)

---

**Happy coding! 🚀**
