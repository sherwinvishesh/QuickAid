# QuickAid

![Static Badge](https://img.shields.io/badge/Google_AI_Hackathon-_Project_Submitted-blue)
![Static Badge](https://img.shields.io/badge/MedHacks_Season_2-_Project_Submitted-blue)
[![View on Devpost](https://img.shields.io/badge/View_Project-On%20Devpost-blue)](https://devpost.com/software/911v2)

QuickAid is an advanced virtual first-aid tool capable of promptly identifying injuries from uploaded images and providing corresponding treatment recommendations. This tool enhances the efficacy of initial medical responses by leveraging powerful AI technology to make quick and accurate assessments accessible to everyone.

## Features
- **Injury Identification**: Users can upload images of injuries, and QuickAid identifies them using advanced image recognition technology.
- **Treatment Recommendations**: After identifying an injury, the tool provides step-by-step treatment recommendations based on best medical practices.
- **Accessible User Interface**: Designed to be user-friendly, QuickAid ensures that critical information is accessible to individuals in emergency situations, including those with limited mobility or visual impairments.

## User Interface 
https://github.com/sherwinvishesh/QuickAid/assets/60791187/a60977d3-3e25-4fa9-8b97-467697cd126c



## Installation

To run QuickAid on your local machine, you need Python 3.6+ installed. Follow these steps:

1. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/sherwinvishesh/QuickAid.git
    ```
2. Navigate to the project directory.
    ```bash
    cd QuickAid
    ```
3. Install the required Python packages.
    ```bash
    pip3 install -r requirements.txt

    ```
    `If you are getting any errors while installing the above`
    Then you have to create a virtual environment and run this program, here are the steps:
    Create a Virtual Environment:
    ```bash
    python3 -m venv path/to/venv
    ```
    Activate the Virtual Environment:
    mac or linux 
    ```bash
    source path/to/venv/bin/activate
    ```

    For Windows:
    ```bash
    path\to\venv\Scripts\activate
    ```

4. Set Up Environment Variables
   Create a `.env` file in the root directory and add your API keys and other sensitive data:
   ```plaintext
   API_KEY='your_api_key_here'
   ```


5. Run the Flask application.
    ```bash
    python3 app.py
    ```




## Usage

To use QuickAid, follow these simple steps:

1. **Open the Application**: Go to `http://127.0.0.1:5000/` on your web browser.
2. **Upload an Image**: Click on the 'Browse Images' button to upload an image of the injury.
3. **Receive Information**: QuickAid will analyze the image and provide a detailed description of the injury along with step-by-step treatment advice.



## Technologies Used

QuickAid leverages cutting-edge technologies to provide a robust and user-friendly virtual first-aid assistance platform. Here's an overview of the key technologies:

### Google GenerativeAI (Gemini)

- **Overview**: Google's GenerativeAI i.e. Gemini is at the heart of QuickAid's ability to analyze and interpret medical images. This advanced AI technology enables the application to understand the context of an injury from an image and generate accurate descriptions and treatment recommendations.
- **Role in QuickAid**: We utilize the GenerativeAI's capabilities to transform visual data into actionable medical advice, significantly reducing the response time in critical situations.

### Flask

- **Overview**: Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications.
- **Role in QuickAid**: Flask serves as the backbone of our application, handling web requests, serving the web pages, and linking the frontend with our AI models. Its simplicity and flexibility allow us to rapidly develop and iterate on our web interface.

### Pillow (PIL Fork)

- **Overview**: Pillow is the friendly PIL fork by Alex Clark and Contributors. PIL (Python Imaging Library) adds image processing capabilities to your Python interpreter. This library supports a wide variety of image file formats and provides powerful image processing and graphics capabilities.
- **Role in QuickAid**: Pillow is used in QuickAid for opening, manipulating, and saving many different image file formats. This is crucial for the preprocessing of images before they are analyzed by our AI models.

### Integration

These technologies are integrated into a seamless workflow that ensures QuickAid is not only highly effective but also user-friendly and accessible to people with no technical background. The combination of Google's powerful Gemini AI analysis tools with Flask's web capabilities and Pillow's image processing allows QuickAid to deliver fast and reliable medical guidance.




## Contributing

Contributions to enhance this project are welcomed. Please feel free to fork the repository, make changes, and submit pull requests.

## Support

If you encounter any issues or have any questions, please submit an issue on the GitHub issue tracker or feel free to contact me.


## License

QuickAid is open source and available under the [Apache-2.0 license](LICENSE).

## Acknowledgments

- Immense gratitude to `Google` for hosting the hackathon that served as a launching pad for QuickAid. Their commitment to nurturing innovation in the AI space has not only provided us with a platform to present our work but has also been a cornerstone of our development journey.


- Heartfelt thanks to all who visit and engage with QuickAid. Your interest, usage, and feedback are the driving forces behind our continuous improvement and innovation. We're committed to delivering value and enhancing your  experience, inspired by your support and insights.


## Connect with Me

Feel free to reach out and connect with me on [LinkedIn](https://www.linkedin.com/in/sherwinvishesh) or [Instagram](https://www.instagram.com/sherwinvishesh/).




## Disclaimer

QuickAid is an advanced virtual first-aid assistant designed to provide preliminary guidance based on images of injuries. The advice provided by QuickAid is based on general medical knowledge and is not a substitute for professional medical advice, diagnosis, or treatment.

### Points to Consider:

- **Non-Professional Advice**: The information and recommendations provided by QuickAid are for informational purposes only and are not intended to replace or represent the professional judgment of healthcare providers in diagnosing and treating patients.

- **Accuracy**: While we strive to provide accurate and up-to-date medical information, QuickAid cannot guarantee the correctness or completeness of the content available through the service.

- **Liability**: Neither the developers of QuickAid nor any other party involved in the creation, production, or delivery of the information be liable for any direct, indirect, incidental, consequential, special, or punitive damages arising out of your access to, or use of, QuickAid.


### User Responsibility:

It is the responsibility of the user to evaluate the information and content provided by QuickAid. Reliance on any information provided by QuickAid is solely at your own risk. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.

---

Made with ❤️ by Sherwin
