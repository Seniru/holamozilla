# Hola Mozilla Web

A website for the "Hola Mozilla" orientation program organized by the Mozilla Campus Club of SLIIT. It features an event hero, carousel, contact links, and a ticket generator that renders a downloadable ticket image.


### Figma Design
[View the Figma design](https://www.figma.com/design/divsaqMRw8UTKhdkPzpk14/HolaMozilla-2025-Web)


## Features
- Hero section with event date and countdown
- Carousel of past event images
- Contact us page
- Ticket generator that draws on a canvas and downloads as PNG

## Tech Stack
- React 17 (Create React App)
- react-router-dom for routing
- Font Awesome for icons
- Plain CSS modules

## Getting Started
Requirements: Node.js and npm

1. Install dependencies:
	 ```bash
	 npm install
	 ```
2. Start development server:
	 ```bash
	 npm start
	 ```
	 The app will open at http://localhost:3000

## Project Structure
- `src/`
	- `App.js` — router and routes
	- `index.js` — React entry
	- `components/`
		- `Header/` — site header
		- `Hero/` — hero + countdown
		- `Carousel/` — carousel component
		- `Ticket/` — canvas ticket generator
		- `CountdownTimer/` — countdown logic
	- `pages/`
		- `Index/` — landing page
		- `Ticket/` — ticket page
		- `Contact/` — contact page
		- `register/` — register page
- `public/`
	- `index.html` — HTML template
	- `images/` — public images

## License
This project is licensed under the Mozilla Public License 2.0 (MPL 2.0).
See the LICENSE file for details.
