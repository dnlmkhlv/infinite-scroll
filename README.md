# Infinite Scroll with Unsplash API

This project demonstrates an infinite scroll feature using the Unsplash API to load high-quality images. As users scroll down the page, new images are dynamically loaded, creating a seamless browsing experience.

## Features

- Infinite scrolling of images
- High-quality images from Unsplash
- Responsive design
- Lazy loading for improved performance

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Unsplash API

## Setup

1. Clone the repository: 
```
git clone https://github.com/dnlmkhlv/infinite-scroll-unsplash.git
```

2. Navigate to the project directory:
```
cd infinite-scroll
```

3. Create a `config.js` file in the root directory with your Unsplash API key:
```
const config = {
  UNSPLASH_ACCESS_KEY: 'your_unsplash_access_key_here'
};
```

4. Open index.html in your web browser.

## Configuration
To use this project, you need to sign up for an Unsplash developer account and obtain an API key. Once you have your key, add it to the config.js file as shown in the setup instructions.

## Usage
Simply scroll down the page to load more images. The application will automatically fetch and display new images as you approach the bottom of the page.

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

## Acknowledgements
- Unsplash for providing the API and amazing photos
- Unsplash JavaScript API Client for simplifying API interactions
