# Major_Project
Image Steganography

Overview

This project is a graphical user interface (GUI) application for image steganography, which involves hiding and revealing secret data (text) within an image using the least significant bit (LSB) technique provided by the `stegano` package.

Features

Hide secret data within an image using LSB technique.
Reveal hidden data from an image using LSB technique.
Save the modified image with hidden data.
User-friendly interface for easy navigation and operation.

Prerequisites

Python 3.x installed.
Required Python packages: `tkinter`, `PIL` (Python Imaging Library), and `stegano`.

You can install the required packages using the following commands:
shell
pip install pillow
pip install stegano


Installation and Setup

1. Clone the repository: Clone the project repository to your local machine.

   shell
   git clone <repository-url>
    

2. Navigate to the project directory: Use the `cd` command to navigate to the project directory.

   shell
   cd <project-directory>
    

3. Run the Python script**: Execute the Python script to launch the application.

   shell
   python image_steganography.py
    

Usage

Open Image: Click the "Open Image" button to select an image file you want to work with.
Hide Data: Enter the secret data in the text box and click the "Hide Data" button to hide the data within the image.
Show Data: Click the "Show Data" button to reveal and display the hidden data from the image.
Save Image: After hiding data in an image, you can save the modified image by clicking the "Save Image" button.
Exit: Click the "Exit" button to close the application.

Project Structure

image_steganography.py`: Main Python script containing the GUI and project functionalities.
her image files (e.g., `logo.jpg`, `computer.png`) may be required for the application.

Troubleshooting

Ensure you have installed the required Python packages.
Make sure the image file selected is in a supported format (e.g., PNG, JPG).
If you encounter any other issues, verify the file paths and required dependencies.

License

This project is open source and available under the MIT License.

---

Thank you for using this application! If you encounter any issues or have any suggestions, please feel free to contact the project maintainer.
