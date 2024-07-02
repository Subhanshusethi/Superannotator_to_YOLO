<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JSON to TXT Converter and Label Mapper</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2, h3 {
            color: #333;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border: 1px solid #ccc;
            overflow-x: auto;
        }
        code {
            font-family: monospace;
            font-size: 1em;
        }
    </style>
</head>
<body>
    <h1>JSON to TXT Converter and Label Mapper</h1>

    <h2>Overview</h2>
    <p>
        This project contains scripts to convert JSON files with object detection data into normalized text files,
        and to map label values in text files to new values based on specified rules.
    </p>

    <h2>Scripts</h2>
    <ul>
        <li><strong>Label Mapper:</strong> Maps label values in text files to new values.</li>
        <li><strong>JSON to TXT Converter:</strong> Converts JSON files to text files with normalized coordinates.</li>
    </ul>

    <h2>File Structure</h2>
    <pre><code>
project_root/
│
├── label_mapper.py
├── json_to_txt_converter.py
└── README.html
    </code></pre>

    <h2>Setup</h2>
    <h3>Prerequisites</h3>
    <ul>
        <li>Python 3.x</li>
        <li><code>os</code> module (part of Python Standard Library)</li>
        <li><code>json</code> module (part of Python Standard Library)</li>
    </ul>

    <h3>Installation</h3>
    <ol>
        <li>Clone the repository:</li>
    </ol>
    <pre><code>git clone https://github.com/your-username/your-repo-name.git</code></pre>
    <ol start="2">
        <li>Navigate to the project directory:</li>
    </ol>
    <pre><code>cd your-repo-name</code></pre>

    <h2>Usage</h2>

    <h3>Label Mapper</h3>
    <p>
        The <code>label_mapper.py</code> script maps label values in text files to new values based on specified rules.
    </p>
    <ol>
        <li>Place your label text files in the specified directory (<code>C:/Users/haZAR/Desktop/New folder/valid/labels</code>).</li>
        <li>Run the script:</li>
    </ol>
    <pre><code>python label_mapper.py</code></pre>

    <h3>JSON to TXT Converter</h3>
    <p>
        The <code>json_to_txt_converter.py</code> script converts JSON files containing object detection data into text files with normalized coordinates.
    </p>
    <ol>
        <li>Place your JSON files in the specified directory (<code>C:/Users/haZAR/Desktop/New folder/hello</code>).</li>
        <li>Run the script:</li>
    </ol>
    <pre><code>python json_to_txt_converter.py</code></pre>

    <h2>Contributing</h2>
    <p>
        Feel free to open issues or submit pull requests if you have suggestions for improvements or find any bugs.
    </p>

    <h2>License</h2>
    <p>
        This project is licensed under the MIT License.
    </p>
</body>
</html>
