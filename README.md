##Video Streaming Flask Application

This Flask application demonstrates live video streaming using OpenCV and Flask. It captures video from the device's camera and streams it to a web page using Flask's `multipart/x-mixed-replace` content type.

 Prerequisites

- Python 3.x
- Flask
- OpenCV

##Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/your-video-streaming-app.git
    cd your-video-streaming-app
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask application:

    ```bash
    python app.py
    ```

4. Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to see the live video streaming.

## Folder Structure

- **templates:** Contains HTML templates for the Flask application.
- **static:** Contains static files such as CSS.

## Files

- **app.py:** The main Flask application file.
- **templates/index.html:** HTML template for the web page.
- **static/styles.css:** CSS styles for the web page.

## Customize

Feel free to customize the application based on your requirements. You can modify the HTML template (`index.html`) and CSS styles (`styles.css`) to change the appearance and layout of the web page.

## Troubleshooting

If you encounter any issues, make sure to check the following:

- Ensure Python and the required dependencies are installed.
- Verify the camera is accessible and working on your device.

## Acknowledgements

This project is based on the Flask framework and utilizes the OpenCV library for video streaming.

