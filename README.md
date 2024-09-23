# Resume-
LaTeX Resume Template
This repository contains a clean and simple resume template written in LaTeX. The template is designed to be highly customizable, allowing users to easily adjust content, formatting, and layout to suit their personal needs.

Features
Simple, elegant design with sections for Education, Skills, and Awards.
Customizable contact information and profile picture.
Flexible table formatting for easy degree listings.
Uses standard LaTeX packages (geometry, graphicx, array) for easy compilation and tweaking.
Preview
Resume Preview

How to Use
Clone this repository:

git clone https://github.com/your-username/latex-resume.git
Replace the content:

Open the main.tex file.
Replace the default name, address, education details, and skills with your own information.
If you have a photo, replace passport_photo.jpg with your own image. You can adjust the dimensions in the code if necessary.
Compile the LaTeX document: You can use any LaTeX editor such as Overleaf or compile locally with pdflatex:

pdflatex main.tex
Add or customize sections:

You can add more sections like "Work Experience" or "Projects" by copying the format of existing sections (e.g., \section*{}).
Customize the table sizes or image dimensions as needed.
Requirements
You need a LaTeX distribution installed on your machine. For local compilation, you can use:

TeX Live (Linux/Windows)
MacTeX (macOS)
Required LaTeX packages:

geometry
graphicx
array
File Structure
latex-resume/ │ ├── main.tex # The main LaTeX file for the resume ├── passport_photo.jpg # Example image (replace with your own) └── README.md # This readme file
