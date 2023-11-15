# WEB WHITEBOARD
#### Video Demo:  <URL https://youtu.be/OAR8Izl6Abs>
#### Description:

Welcome to my CS50x final project! I'm Hamid Fenzi from Algiers, Algeria. This project aims to contribute to making knowledge accessible to everyone worldwide, fostering better development. As a beginner in programming, I aimed to create something simple, yet meaningful: a web whiteboard.

## Project Structure

### Files
- **layout.html:** This file serves as the Python Flask Jinja base for the project. It acts as the foundation for the two other main files, home.html, and index.html.
- **home.html:** Functioning as a screensaver, this file features an animated canvas inspired by Codeply. I made significant modifications, including the ability to change the color and shadow of the satisfying curly cursor. When the whiteboard button is clicked, it redirects to index.html.
- **index.html:** This is the main whiteboard implementation page. Users can choose from various paper-lined backgrounds or a blank canvas. The interface includes tools such as clear, undo, redo, size adjustment, color changer, eraser, pencil, and a file input option to load images from the local drive.

### JavaScript Files
- **canv_h.js:** This file contains the JavaScript code for the animated canvas in home.html, with additional features such as color and shadow modification for the cursor.
- **canv.js:** The JavaScript code for the whiteboard canvas in index.html, featuring tools for drawing, clearing, undoing, redoing, and more.

### Static Folder
- **js Folder:** Contains the JavaScript files (canv_h.js and canv.js) for the project.
- **css Folder:** Holds the style.css file for styling the web application.
- **image Folder:** Contains images used for paper-lined backgrounds.

### Root Folder
- **.gitignore:** Ignores the venv virtual environment folder when pushing the project to GitHub.
- **app.py:** Runs the web application.
- **README.md:** This document explaining the project.
- **requirements.txt:** Lists the requirements to run the project.
- **vercel.json:** Configuration file for hosting and deploying on Vercel.

## Features

- **Canvas Customization**: Choose between a blank page background or several paper-lined backgrounds.
- **Drawing Tools**: Buttons for pencil, eraser, color changer, and size adjustment.
- **Undo and Redo**: Easily correct or repeat actions.
- **File Input**: Load images from the local drive for reference or annotation.

## Getting Started
To run the project locally, make sure you have Python and Flask installed. Then, run the following commands in your terminal:

```bash
pip install Flask
python app.py
```

Visit [http://localhost:5000](http://localhost:5000) in your web browser to explore the whiteboard application.

## Live Demo

You can explore the Whiteboard project live at [https://hamidfenzi.vercel.app/](https://hamidfenzi.vercel.app/).

## Contributing
Contributions to improve the functionality, design, or any other aspect of the whiteboard project are welcome. Feel free to fork the repository and submit pull requests.

## Acknowledgments
- CS50 for providing the foundation for this project.
- Codeply for inspiration in the animated canvas on `home.html`.

## Project Potential

This project has the potential to evolve into a powerful tool for disseminating knowledge globally. By reducing ignorance and making information accessible to all, it could contribute significantly to the betterment of the world.