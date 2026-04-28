# TechShelf 📱

This is a responsive e-commerce web application built with React and TypeScript. It simulates a real online store where users can browse phones, tablets, and accessories, add them to the cart, and save their favorites.

## 🚀 Demo

[Live Version](https://roma-ivashchenko.github.io/gadget-store-react/)

## ✅ Key Features:

- **Advanced Search & Filtering:** Products can be sorted by age, title, or price. The search query, sorting, and pagination state are strictly synchronized with the URL (`useSearchParams`), allowing users to share specific views.
- **Dynamic Product Pages:** Users can select different colors and memory capacities. The URL and product details update dynamically based on the selected variant.
- **Shopping Cart & Favorites:** Users can add items to the cart, adjust quantities, or remove them. Favorites are preserved using `LocalStorage`.
- **Home Page Promos:** Implemented a main promotional slider and distinct carousels for "Brand new models" and "Hot prices".
- **Responsive Design:** Fluid layout that adapts seamlessly to mobile, tablet, and desktop screens.
- **Breadcrumbs:** Intuitive navigation to easily track the current category path.

## 🛠 Tech Stack & Tools:

- **React** (Hooks, Context API)
- **TypeScript** (For static typing and reducing runtime errors)
- **SCSS Modules** (For scoped, maintainable styling)
- **React Router** (For routing and URL parameters management)
- **Swiper** (For touch-friendly sliders)
- **Lodash.debounce** (For optimizing search input performance)

## 📦 How to run locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/Roma-Ivashchenko/gadget-store-react.git]
   ```
2. Navigate to the project folder:
   cd gadget-store-react

3. Install dependencies:
   npm install

4. Start the development server:

   npm start
