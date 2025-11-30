# 🌿 Paradise Nursery Shopping Application

> **Where Green Meets Serenity**

A fully functional e-commerce shopping cart application built with React and Redux Toolkit, featuring a beautiful collection of 30 plants across 5 categories.

![Project Status](https://img.shields.io/badge/Status-Complete-success)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)
![React](https://img.shields.io/badge/React-18-blue)
![Redux](https://img.shields.io/badge/Redux-Toolkit-purple)

---

## ✨ Features

- 🌿 **30 Beautiful Plants** across 5 categories
- 🛒 **Shopping Cart** with full CRUD operations
- 💰 **Real-time Price Calculations**
- 🔢 **Increment/Decrement Quantities**
- 🏷️ **Cart Quantity Badge** on navigation
- ✅ **"Added to Cart" Feedback** with disabled state
- 📱 **Responsive Design** for all devices
- ⚡ **Redux State Management** for global state
- 🎨 **Modern UI/UX** with clean design

---

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Git

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/[your-username]/e-plantShopping.git
cd e-plantShopping
```

2. **Install dependencies:**
```bash
npm install
```

3. **Run development server:**
```bash
npm run dev
```

4. **Open browser:**
Navigate to `http://localhost:5173`

---

## 📦 Available Scripts

```bash
npm run dev       # Start development server
npm run build     # Build for production
npm run preview   # Preview production build
npm run deploy    # Deploy to GitHub Pages
```

---

## 🏗️ Project Structure

```
e-plantShopping/
├── src/
│   ├── App.jsx              # Main application component
│   ├── ProductList.jsx      # Product catalog with cart integration
│   ├── CartItem.jsx         # Shopping cart component
│   ├── CartSlice.jsx        # Redux cart state management
│   ├── store.js             # Redux store configuration
│   ├── main.jsx             # Application entry point
│   ├── AboutUs.jsx          # About section
│   └── *.css                # Component styles
├── public/                  # Static assets
├── dist/                    # Production build
└── package.json             # Project dependencies
```

---

## 🎯 Plant Categories

1. **Air Purifying Plants** - Improve indoor air quality
2. **Aromatic Fragrant Plants** - Delightful scents for your space
3. **Insect Repellent Plants** - Natural pest control
4. **Medicinal Plants** - Therapeutic and healing properties
5. **Low Maintenance Plants** - Easy care for busy lifestyles

---

## 💻 Technologies Used

- **React 18** - UI library
- **Redux Toolkit** - State management
- **Vite** - Build tool and dev server
- **CSS3** - Styling
- **React Redux** - React bindings for Redux
- **gh-pages** - Deployment

---

## 🎨 Key Components

### ProductList Component
- Displays all plants in a responsive grid
- Handles "Add to Cart" functionality
- Shows cart quantity badge
- Manages navigation between views

### CartItem Component
- Displays cart contents
- Increment/decrement quantities
- Remove items functionality
- Calculates totals and subtotals
- Continue shopping and checkout options

### CartSlice (Redux)
- `addItem` - Add products to cart
- `removeItem` - Remove products from cart
- `updateQuantity` - Update product quantities

---

## 🌐 Live Demo

Visit the live application:
```
https://[your-username].github.io/e-plantShopping/
```

---

## 🚀 Deployment

Deploy to GitHub Pages:

```bash
npm run deploy
```

Then enable GitHub Pages in your repository settings:
1. Go to **Settings** → **Pages**
2. Select **gh-pages** branch
3. Click **Save**

---

## 📖 Documentation

Comprehensive documentation available in:
- `FINAL_SUMMARY.md` - Complete project summary
- `IMPLEMENTATION_GUIDE.md` - Detailed implementation guide
- `QUICK_START.md` - Quick start guide
- `PROJECT_COMPLETION.md` - Full completion report

---

## ✅ Features Implemented

- [x] Product listing with 30 plants
- [x] Add to cart functionality
- [x] Shopping cart with item management
- [x] Increment/decrement quantities
- [x] Remove items from cart
- [x] Real-time price calculations
- [x] Cart quantity badge
- [x] Redux state management
- [x] Responsive design
- [x] Navigation between pages
- [x] Button state management
- [x] Persistent cart state

---

## 🤝 Contributing

This is a learning project created as part of a course assignment. Feel free to fork and experiment!

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- IBM Developer Skills Network for the project template
- React and Redux communities for excellent documentation
- Pixabay and Unsplash for beautiful plant images

---

## 📞 Support

For issues or questions:
1. Check the documentation files
2. Review console errors (F12)
3. Ensure all dependencies are installed
4. Verify Node.js version compatibility

---

## 🎯 Learning Objectives Achieved

- ✅ React functional components
- ✅ React hooks (useState, useEffect, useSelector, useDispatch)
- ✅ Redux Toolkit configuration
- ✅ Redux slices and reducers
- ✅ Global state management
- ✅ Array methods and data manipulation
- ✅ Event handling
- ✅ Conditional rendering
- ✅ Component composition
- ✅ CSS styling and responsive design

---

**🌿 Paradise Nursery - Bringing Nature to Your Home 🌿**

*Built with ❤️ using React and Redux*