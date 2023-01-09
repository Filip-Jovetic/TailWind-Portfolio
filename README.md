# TailWind-Portfolio

In this project, we build a responsive SPA using the tailwind framework.
#can work with UI controls


# Installation

Install tailwindcss via npm, and create your tailwind.config.js file.

# Node
Node is really easy to install & now include NPM. You should be able to run the following command after the installation procedure below.

$ node --version
v0.10.24

$ npm --version
1.3.21

# Configuration

Add the paths to all of your template files in your tailwind.config.js file.

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
