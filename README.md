# colab-astro_SDSS
ProjectS4: SDSS Image Access

Description:

The SDSS Image Viewer is a Python application designed to retrieve, visualize, and display astronomical images from the Sloan Digital Sky Survey (SDSS) database. Built upon the foundation of ProjectS3 and ProjectS4, this tool extends the exploration of astronomical data by providing users with the ability to access and analyze images of celestial objects with ease and flexibility.

Features:

Image Retrieval: Users can specify coordinates (Right Ascension and Declination) to retrieve images from the SDSS database. Images can be obtained individually or within a specified range of coordinates.

Customization: Users can customize the scale of the images and choose from different options for image processing (e.g., 'L' for grayscale).

Image Display: Retrieved images are displayed in a grid layout using the Tkinter library. The application automatically adjusts the layout based on the number of images retrieved.

Organization: Retrieved images are saved in a folder named 'images' within the project directory. Images are organized and labeled based on their celestial coordinates, facilitating easy identification and analysis.

Dependencies:

Python 3.x
Requests library
Tkinter library
PIL (Python Imaging Library)

Usage:

Ensure Python and the required libraries are installed.
Run the provided code in a Python environment.
Specify the desired coordinates, scale, and other parameters as needed.
Execute the display_images function to retrieve and display the images.
Example:

python
Copy code
display_images(ra_min=120, ra_max=130, dec_min=30, dec_max=40, scale=0.1, step=1)
This example retrieves and displays images from the region of the sky with Right Ascension ranging from 120 to 130 and Declination ranging from 30 to 40, with a scale of 0.1 and a step size of 1.

Note:

The application requires an active internet connection to retrieve images from the SDSS database.
Users are encouraged to explore the code and customize it according to their specific needs and preferences.
For any issues or inquiries, please refer to the documentation or contact the project maintainers.
Contributors:

Elen Aghalovyan/ i21.aghalovyan.elen@etud.ufar.am
Zhanna Minasyan/ i21.minasyan.zhanna@etud.ufar.am
Davit Azarumyan/ i21.azarumyan.davit@etud.ufar.am


License:

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments:

Special thanks to the Sloan Digital Sky Survey (SDSS) for providing access to their extensive database of astronomical images and data.
