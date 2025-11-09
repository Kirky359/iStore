# IStore

This project is a feature-rich front-end for an e-commerce store specializing in mobile phones, tablets, and accessories. It provides a clean, modern, and responsive user interface for customers to browse products, view details, filter, sort, and manage their favorite items and shopping cart.

## Live Preview

You can view the deployed version of the project here:
[DEMO LINK](https://Kirky359.github.io/iStore/)

## Design Reference

The project's design is based on the following Figma file.
[Figma - Phone catalog V2 (Dark)](https://www.figma.com/design/BUusqCIMAWALqfBahnyIiH/Phone-catalog--V2--Original-Dark?node-id=0-1&p=f)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need to have **Node.js** and **npm** (or yarn) installed on your machine.

### Installation & Running

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Kirky359/IStore.git](https://github.com/Kirky359/IStore.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd IStore
    ```

3.  **Install NPM packages:**
    ```bash
    npm install
    ```

4.  **Start the project:**
    ```bash
    npm start
    ```
    The application will be available at `http://localhost:5173/` (or another port if 5173 is busy).

## 💻 Technologies Used

* **Core**
    * **React** – UI framework
    * **TypeScript** – Type safety
    * **SCSS** – Styling

* **State Management**
    * **React Context** – Global state management for features like the shopping cart and favorites.

* **UI/UX**
    * **React Router** – Navigation
    * **Swiper** – Image galleries
    * **React-Alert** – To display notifications to the user.

* **Development & Deployment**
    * **Vite** – Build tool
    * **ESLint** – Code quality

## Features

* **Favorites:** Ability to add and remove products from a "Favorites" list, with a persistent counter in the header.
* **Shopping Cart:** Fully functional shopping cart to add and remove items, view total price, and adjust quantities.
* **Responsive Design:** The layout is fully adaptive for a seamless experience on mobile, tablet, and desktop devices.
