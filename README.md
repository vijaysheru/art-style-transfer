# Artistic Style Transfer

Artistic Vision Transfer is a web application that transforms your photos into stunning artworks using neural style transfer techniques. This project leverages Flask for the web framework and TensorFlow for the style transfer model.

## Project Overview

The goal of this project is to provide users with an easy-to-use interface to apply artistic styles to their images. Users can upload a content image and a style image, and the application will generate a new image that combines the content of the first with the style of the second.

## Features

- **Neural Style Transfer:** Apply artistic styles to images using pre-trained models.
- **Responsive UI:** Built with Bootstrap for a clean and responsive design.
- **Dynamic Image Display:** Shows the transformed image directly on the webpage.

## Technologies Used

- **Flask:** Web framework for building the application.
- **TensorFlow & TensorFlow Hub:** For implementing neural style transfer.
- **Bootstrap:** For responsive and modern UI design.
- **JavaScript:** For handling form submissions and displaying results dynamically.

## Installation

### Prerequisites

- Python 3.7 or later
- Virtual environment (recommended)
- Git

### Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/<your-username>/art-style-transfer.git
   cd art-style-transfer
2. **Create a Virtual Environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
4. **Run the Application:**
   ```bash
   python app.py
5. **Access the Application:**

   Open your browser and go to http://localhost:5001 to use the application.

   
### Usage

1. Upload a content image and a style image using the provided form.
2. Click "Transform" to apply the style transfer.
3. View and download your stylized image once processing is complete.

### Project Design

The application is designed using Flask as the backend framework, handling requests and serving HTML templates. TensorFlow is used for performing neural style transfer, leveraging pre-trained models from TensorFlow Hub. The frontend is styled with Bootstrap to ensure responsiveness across different devices.


### State of the Art

Neural style transfer is an advanced technique in computer vision that applies artistic styles to images by optimizing feature representations from deep neural networks. This project uses state-of-the-art models from TensorFlow Hub, which are efficient and produce high-quality results.

### Project Milestones

- Initial setup of Flask application and basic UI design.
- Integration of TensorFlow model for style transfer.
- Implementation of responsive design using Bootstrap.
- Testing and optimization for performance improvements.
- Deployment on a cloud platform for continuous operation.

  
### Expected Results

The project aims to deliver a fully functional web application that allows users to transform their images with artistic styles. Success will be measured by the application's ability to handle multiple users simultaneously and produce high-quality stylized images within seconds.

### Reference Material

- TensorFlow Hub for pre-trained models.
- Flask Documentation for web development guidance.
- Bootstrap Documentation for responsive design tips.
  
### Contributing

Contributions are welcome! Please fork this repository and submit pull requests with any improvements or bug fixes.


### License

This project is licensed under the MIT License - see the LICENSE file for details.


### Acknowledgments
Inspired by various neural style transfer projects and tutorials available online.
Special thanks to contributors and open-source libraries used in this project.
