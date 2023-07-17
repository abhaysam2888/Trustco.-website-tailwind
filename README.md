
# Trustco. website build using Tailwind

Tailwind CSS refers to the utilization of the framework's more intricate features and techniques to create highly customized and complex user interfaces. Some key aspects of advanced Tailwind CSS include:

- Customization:

- Component Styling:

- Responsive Design:

- Extended Utility Classes:

Creating a Trustco website clone using HTML and Tailwind CSS can be a challenging yet rewarding project that allows me to practice my frontend development skills while emulating the design and functionality of Trustco's official website.

To begin, you would utilize HTML to structure the layout and content of the website. Analyzing the original Trustco website, you would identify the key sections such as the homepage, about us, services, and contact pages. Using HTML tags and elements, you would create the necessary structure for each page, ensuring proper semantic markup and accessibility.

Next, Tailwind CSS would come into play for styling the clone. By leveraging Tailwind CSS's utility classes, you can easily apply styles to the HTML elements. Tailwind CSS provides a wide range of pre-defined classes for typography, colors, spacing, and more, enabling you to closely replicate the visual appearance of the original website.

To enhance the responsiveness of the Trustco website clone, you would utilize Tailwind CSS's responsive utility classes. These classes allow you to create a layout that adapts seamlessly to different screen sizes, ensuring an optimal user experience across various devices.

Additionally, you may incorporate custom CSS to handle any specific styling requirements that Tailwind CSS might not cover. This would involve writing CSS rules to target specific elements and override or extend the default styles provided by Tailwind CSS.

Throughout the development process, it is important to reference the original Trustco website for design inspiration, color schemes, and branding elements. By closely aligning the clone with the original website, you can create a visually consistent and recognizable experience for users.

By creating a Trustco website clone using HTML and Tailwind CSS, you can gain valuable experience in frontend development, responsive design, and styling using a utility-first CSS framework. It is an excellent opportunity to showcase your skills and attention to detail while replicating the look and feel of a reputable financial services website.


## Tech Stack

- HTML, Taliwind CSS


## Features
- Fully Resposive
- 100% made with Tailwind CSS
- Attractive design 
## Installation

Install Tailwind CSS

```bash
    Step 1:- open Terminal and run (npx tailwindcss init).
```
```bash
    Step 2:- Add folder dist and under a folder a file #output.css and code file name ex-index.html
```
```bash
   step 3:- Add another folder src and under a folder a file #inputput.css
```
```bash
  step 4:- Add codes in input.css file

@tailwind base;
@tailwind components;
@tailwind utilities;
```
```bash
  step 5:- write .dist/*.html in config.js file

module.exports = {
  content: [".dist/*.html"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
```bash
  step 6:- All done jus run a code in terminal 

npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
```bash
  step 7:- Add <link rel="stylesheet" href="output.css"> in html file
```
```bash
   Note:- You must install node js to run this programm
```


    
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/abhaysam2888?tab=repositories)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhay-verma-821699274/)


