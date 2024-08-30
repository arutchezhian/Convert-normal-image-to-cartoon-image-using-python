<h1 align="center">Normal Image to Cartoon Image using Python</h1>

<h2>Overview</h2>

<p>This project converts normal images into cartoon-style images using Python. It utilizes Gradio for a user-friendly interface and integrates with Hugging Face for machine learning model deployment.</p>

<h2>File Structure</h2>

<ul>
    <li><b>main.py</b>: Main script to run the cartoon image generation.</li>
    <li><b>requirements.txt</b>: Contains the list of dependencies required to run the project.</li>
    <li><b>utils.py</b>: Utility functions used in the project for image processing.</li>
    <li><b>model.py</b>: Script that loads and processes the machine learning model for style transfer.</li>
    <li><b>interface.py</b>: Script that sets up the Gradio UI for interacting with the model.</li>
</ul>

<h2>Usage</h2>

<ol>
    <li>Install Python 3.x and the required libraries from <code>requirements.txt</code>.</li>
    <li>Clone or download the project repository.</li>
    <li>Choose the appropriate script (<code>main.py</code>, <code>interface.py</code>) based on your use case.</li>
    <li>Run the selected script to start the image conversion or interact with the UI.</li>
</ol>

<h3>Example Usage</h3>

<p>For image conversion using the model:</p>

<pre><code>python main.py --input_image path/to/image.jpg --output_image path/to/output.jpg</code></pre>

<p>To launch the Gradio UI for interactive usage:</p>

<pre><code>python interface.py</code></pre>

<h2>Contributing</h2>

<p>Contributions are welcome! If you have suggestions, bug reports, or enhancements, feel free to open an issue or create a pull request.</p>
