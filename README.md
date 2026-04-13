
# 🔗 URL Shortener

A sleek, functional URL shortener built with modern web technologies. This application allows users to transform long, cumbersome URLs into manageable, short links.

## 🚀 Features

* **URL Shortening:** Instantly convert long URLs into short, shareable links.
* **Analytics Dashboard:** Track clicks and monitor the performance of your links.
* **User Authentication:** Secure login and signup functionality.
* **Responsive Design:** Optimized for mobile, tablet, and desktop views.
* **Copy to Clipboard:** Quick one-click copying for shortened links.


## 📦 Installation

To get a local copy up and running, follow these simple steps:

1.  **Clone the repository**
    ```bash
    git clone https://github.com/MinitChitroda/url-shortener.git
    ```

2.  **Navigate to the project directory**
    ```bash
    cd url-shortener
    ```

3.  **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
    ```

4.  **Set up Environment Variables**
    Create a `.env` file in the root directory and add your configuration (refer to `.env.example` if available).

5.  **Run the development server**
    ```bash
    npm run dev
    ```

## 📂 Project Structure

```text
├── public/          # Static assets
├── src/
│   ├── components/  # Reusable UI components
│   ├── pages/       # Application pages/routes
│   ├── App.jsx      # Main App component
│   └── main.jsx     # Entry point
├── .eslintrc.cjs    # Linting rules
├── tailwind.config.js # Tailwind configuration
└── vite.config.js   # Vite configuration
```
