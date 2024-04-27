# QuickAid

## Description
QuickAid is an advanced virtual first-aid tool capable of promptly identifying common injuries from uploaded images and providing corresponding treatment recommendations. This tool enhances the efficacy of initial medical responses by leveraging powerful AI technology to make quick and accurate assessments accessible to everyone.

## Features
- **Injury Identification**: Users can upload images of injuries, and QuickAid identifies them using advanced image recognition technology.
- **Treatment Recommendations**: After identifying an injury, the tool provides step-by-step treatment recommendations based on best medical practices.
- **Accessible User Interface**: Designed to be user-friendly, QuickAid ensures that critical information is accessible to individuals in emergency situations, including those with limited mobility or visual impairments.

## User Interface 
https://github.com/sherwinvishesh/QuickAid/assets/60791187/a60977d3-3e25-4fa9-8b97-467697cd126c



## Installation

To run StrategX on your local machine, you need Python 3.6+ installed. Follow these steps:

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
