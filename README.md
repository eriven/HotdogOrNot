
# HotdogOrNot

![HotdogOrNot](https://img.shields.io/badge/Project-HotdogOrNot-blue) ![License](https://img.shields.io/badge/License-MIT-green)

## Description

**HotdogOrNot** is a machine learning project that uses image classification to determine whether an image contains a hotdog or not. This project leverages deep learning models to provide accurate predictions based on the visual content of images.

## Features

- **Image Classification**: Classify images as "hotdog" or "not hotdog" using pre-trained models.
- **Web Interface**: Simple web interface to upload images and get predictions.
- **Model Integration**: Easily integrates with Hugging Face's API for model predictions.

## Installation

### Prerequisites

Ensure you have Python 3.6+ and pip installed. Clone the repository and install the dependencies:

```bash
git clone https://github.com/eriven/HotdogOrNot.git
cd HotdogOrNot
```

Create a virtual environment and activate it:

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows use `.venv\Scripts\activate`
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Configuration

1. **API Keys**: Set up your Hugging Face API key. Create a `.env` file in the project root and add your key:

   ```env
   HUGGINGFACE_API_KEY=your_huggingface_api_key_here
   ```

2. **Run the Application**: Start the Flask application:

   ```bash
   python web.py
   ```

   The application will be available at `http://127.0.0.1:5000`.

## Usage

1. **Upload an Image**: Go to `http://127.0.0.1:5000` and use the web interface to upload an image.
2. **Get Prediction**: The model will process the image and return whether it is a hotdog or not.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Hugging Face**: For providing the powerful API used in this project.
- **Flask**: For the lightweight web framework.
- **The original Hotdog or Not dataset**: Used for model training and validation.

