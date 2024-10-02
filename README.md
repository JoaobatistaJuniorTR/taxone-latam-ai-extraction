# taxone-latam-ai-extraction

This project performs the transformation of various types of log files into an expected output format. It includes notebooks to process CPU logs from Datadog, process logs extracted from Oracle, and request logs from Datadog. The files are read, processed, and generated in the expected output format, being split every 100k lines.

## Project Structure

<pre>
taxone-lata-ai-extraction/ 
├── requirements.txt
└── src/
    ├── convert-cpu-logs.ipynb
    ├── convert-oracle-logs.ipynb
    └── convert-reqs-logs.ipynb
</pre>

## Notebooks
- **convert-cpu-logs.ipynb**: Transforms files containing CPU metrics from Datadog.
- **convert-oracle-logs.ipynb**: Transforms files of processes extracted from Oracle (big table).
- **convert-reqs-logs.ipynb**: Transforms files containing requests from Datadog.

## Installation
To install the project dependencies, run: <code> pip install -r requirements.txt </code>

## Usage
Within each notebook, specify the file to be read and the final name of the output file. The files will be processed and generated in the expected output format, being split every 100k lines.

1. Open the desired notebook (`convert-cpu-logs.ipynb`, `convert-oracle-logs.ipynb`, or `convert-reqs-logs.ipynb`) in Jupyter Notebook or JupyterLab.
2. Modify the input and output variables as needed.
3. Run all cells in the notebook to process the files.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Numpy

## Contribution
Contributions are welcome! Please open an issue or submit a pull request to contribute to the project.

## Authors
- [Joao Batista Junior](https://github.com/JoaobatistaJuniorTR)
