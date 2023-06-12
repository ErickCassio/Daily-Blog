# Daily Journal

Daily Journal is a blog developed with Node.js, HTML, CSS, JS, and EJS. It's a simple project that allows users to write and publish their daily posts.

## Prerequisites

Make sure you have the following installed on your machine:

- Node.js: [https://nodejs.org](https://nodejs.org)

## Installation

1. Download or clone this repository.
2. Navigate to the project's root directory.
3. Open the terminal and run the following command to install the project dependencies:

   ```bash
   npm install
   npm start

## Usage
1. In the project's root directory, run the following command to start the server:
   ```bash
   npm install
2. Open your web browser and access http://localhost:3000 to view the Daily Journal blog.

## Customization
1. Blog Title: To change the blog's title, open the views/partials/header.ejs file and update the value in the <title> tag.
2. Styles: The blog's styles are defined in the public/styles.css file. Feel free to customize them according to your preferences.
3. Layout and Components: The EJS files in views/ control the blog's layout and components. You can modify them to adjust the blog's appearance.

## Project Structure
├── app.js
├── public/
│ ├── styles.css
│ └── ...
└── views/
├── partials/
│ ├── footer.ejs
│ ├── header.ejs
│ └── ...
├── home.ejs
├── post.ejs
└── ...
  
1. app.js: The main file that starts the server and configures the routes.
2. public/: The directory that contains static files like CSS, JavaScript, and images.
3. views/: The directory that contains the EJS files that control the blog's views.
4. views/partials/: The directory that contains reusable EJS components such as the header, footer, etc.

## Contribution
Contributions are welcome! If you want to improve the project, feel free to open an issue or submit a pull request.
  
## License
This project is licensed under the MIT License.
