<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Flask Image Editor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #2c3e50;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border: 1px solid #ddd;
            overflow-x: auto;
        }
        code {
            font-family: 'Courier New', Courier, monospace;
            background-color: #f4f4f4;
            padding: 2px 4px;
            border-radius: 4px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            text-align: center;
            text-decoration: none;
            outline: none;
            color: #fff;
            background-color: #4CAF50;
            border: none;
            border-radius: 5px;
            box-shadow: 0 4px #999;
        }
        .button:hover {background-color: #3e8e41}
        .button:active {
            background-color: #3e8e41;
            box-shadow: 0 2px #666;
            transform: translateY(2px);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Flask Image Editor</h1>
        <p>This Flask application allows users to upload and edit images. It supports converting images to PNG, JPG, and WebP formats, as well as converting images to grayscale.</p>

  <h2>Features</h2>
        <ul>
            <li>Upload images in various formats (PNG, JPG, JPEG, GIF, WebP)</li>
            <li>Convert images to:
                <ul>
                    <li>PNG</li>
                    <li>JPG</li>
                    <li>WebP</li>
                    <li>Grayscale</li>
                </ul>
            </li>
            <li>Download the processed images</li>
        </ul>

  <h2>Requirements</h2>
        <ul>
            <li>Python 3.x</li>
            <li>Flask</li>
            <li>OpenCV (cv2)</li>
            <li>Werkzeug</li>
        </ul>

  <h2>Installation</h2>
        <ol>
            <li><strong>Install the required packages:</strong>
                <pre><code>pip install -r requirements.txt</code></pre>
            </li>
            <li><strong>Ensure the `uploads` and `static` directories exist:</strong>
                <pre><code>mkdir uploads static</code></pre>
            </li>
        </ol>

  <h2>Usage</h2>
        <ol>
            <li><strong>Run the Flask application:</strong>
                <pre><code>python app.py</code></pre>
            </li>
            <li><strong>Open your browser and go to <a href="http://127.0.0.1:5000/">http://127.0.0.1:5000/</a>.</strong></li>
            <li><strong>Upload an image and select the desired operation.</strong></li>
            <li><strong>Click "Submit" to process the image.</strong></li>
            <li><strong>Download the processed image from the link provided.</strong></li>
        </ol>
    </div>
</body>
</html>
