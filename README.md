<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parking Space Counter Using OpenCV and Python</title>
</head>
<body>
    <h1>Parking Space Counter Using OpenCV and Python</h1>

    <p>This project demonstrates a parking space counter using OpenCV and Python. The system detects and counts available parking spaces in a video feed using computer vision techniques.</p>

    <h2>Project Overview</h2>
    <p>The main goal of this project is to develop a computer vision application that counts the number of available parking spaces in a video. The system processes video frames, analyzes the parking spaces, and displays the count of free and occupied spots.</p>

    <h2>Files</h2>
    <ul>
        <li><code>Parking_space_posintions.py</code>: Script for defining and managing parking space positions.</li>
        <li><code>README.md</code>: This file, providing an overview of the project.</li>
        <li><code>carPark.mp4</code>: Input video file used for parking space detection.</li>
        <li><code>example_image.png</code>: Example image used for visualization or testing.</li>
        <li><code>main.py</code>: Main script for running the parking space counter application.</li>
        <li><code>output.mp4</code>: Output video showing the parking space count annotations.</li>
        <li><code>positions</code>: Binary file containing parking space positions.</li>
        <li><code>requirements.txt</code>: File listing the Python dependencies required for the project.</li>
    </ul>

    <h2>Setup and Installation</h2>
    <p>To set up the project and install the necessary dependencies, follow these steps:</p>
    <ol>
        <li><strong>Clone the Repository</strong>
            <pre><code>git clone https://github.com/yourusername/Parking-Space-Counter-using-OpenCV-Python-Computer-Vision.git
cd Parking-Space-Counter-using-OpenCV-Python-Computer-Vision</code></pre>
        </li>
        <li><strong>Create and Activate a Virtual Environment</strong>
            <pre><code>python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`</code></pre>
        </li>
        <li><strong>Install Dependencies</strong>
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li><strong>Run the Application</strong>
            <pre><code>python main.py</code></pre>
        </li>
    </ol>

    <h2>Output</h2>
    <p>The processed video with parking space count annotations is saved as <code>output.mp4</code>. Here is a preview of the output video:</p>
    <video width="640" height="360" controls>
        <source src="output.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <h2>Dependencies</h2>
    <p>The <code>requirements.txt</code> file includes the necessary Python libraries for this project. Ensure you have the following packages installed:</p>
    <ul>
        <li><code>opencv-python</code></li>
        <li><code>cvzone</code></li>
        <li><code>numpy</code></li>
    </ul>

    <h2>Usage</h2>
    <ol>
        <li><strong>Adjust Parking Space Positions</strong>: Modify <code>Parking_space_posintions.py</code> to set the positions of parking spaces in the video.</li>
        <li><strong>Process the Video</strong>: The <code>main.py</code> script processes the video <code>carPark.mp4</code>, counts the available parking spaces, and saves the output to <code>output.mp4</code>.</li>
    </ol>

    <h2>Contributing</h2>
    <p>Contributions to the project are welcome. Please follow these steps to contribute:</p>
    <ol>
        <li>Fork the repository.</li>
        <li>Create a new branch (<code>git checkout -b feature/your-feature</code>).</li>
        <li>Make your changes.</li>
        <li>Commit your changes (<code>git commit -am 'Add new feature'</code>).</li>
        <li>Push to the branch (<code>git push origin feature/your-feature</code>).</li>
        <li>Create a new Pull Request.</li>
    </ol>

    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>

    <h2>Contact</h2>
    <p>For any questions or issues, please reach out to <a href="mailto:your.email@example.com">your.email@example.com</a>.</p>
</body>
</html>
