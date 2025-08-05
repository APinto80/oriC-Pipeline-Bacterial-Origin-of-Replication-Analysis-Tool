# 🧬 oriC-Pipeline: Bacterial Origin of Replication Analysis Tool

**oriC-Pipeline** is a Jupyter Notebook-based interactive bioinformatics tool designed to identify and visualize the origin of replication (oriC) in bacterial genomes. It uses cumulative GC skew analysis, DnaA-box motif scanning, and interactive visualizations to help researchers investigate bacterial replication origins in a simple, intuitive way.

---

## 🚀 Features

- 🔍 **Analyze any bacterial genome** via:
  - NCBI accession number
  - FASTA file upload
  - Direct genome sequence paste
- 🧮 **Cumulative GC Skew** and **AT Skew** plots
- 🧬 **DnaA-box motif detection** using a position weight matrix (PWM)
- 📊 Interactive genome-wide visualizations (via Plotly)
- ⚙️ Adjustable parameters:
  - Sliding window size
  - Motif detection threshold
- 📁 Export options for:
  - Motif hits as CSV
  - Skew plot as PNG

---

## 🛠 Installation

1. Make sure you have Python 3.9+ installed.
2. Install dependencies:
```bash
pip install -r requirements.txt
```
Or manually:
```bash
pip install biopython plotly ipywidgets pandas kaleido
```

3. (Optional, for widget support in Jupyter)
```bash
jupyter nbextension enable --py widgetsnbextension
```

---

## 📂 Usage

1. Launch the notebook:
```bash
jupyter notebook oriC_analysis.ipynb
```
2. Choose how to input your genome:
   - Enter an NCBI accession number (e.g., `NC_000962.3`)
   - Upload a FASTA file
   - Paste a genome sequence directly
3. Adjust parameters and run analysis.
4. Export results as needed.

---

## 🖼️ Screenshots

Here’s how the tool looks in action:

### 📊 
![GC Skew Plot](https://github.com/APinto80/oriC-Pipeline-Bacterial-Origin-of-Replication-Analysis-Tool/blob/main/Oric%20ex1.png)

### 🧬 
![Motif Output](https://github.com/APinto80/oriC-Pipeline-Bacterial-Origin-of-Replication-Analysis-Tool/blob/main/Oric%20ex2.png)

---

## 🔮 Future Improvements

- 🔧 Add support for more motif types and additional bacterial replication markers  
- 🚀 Implement batch processing for multiple genomes  
- 📊 Enhance visualizations with customizable color schemes and zoom features  
- 💾 Provide direct export options for high-res vector graphics (SVG, PDF)  
- 🤖 Integrate machine learning models to better predict oriC regions  
- 🌐 Develop a web-based interactive version for users without Python setup  
- 🧪 Add automated testing and benchmarking with diverse bacterial genomes  
- 🛠 Improve error handling and provide more detailed user feedback  

---

## 📖 Requirements

- Python 3.9+
- Jupyter Notebook
- biopython
- plotly
- ipywidgets
- pandas
- kaleido

---

## 🙏 Credits

This project was made possible thanks to the following open-source libraries:

- [Biopython](https://biopython.org/) – Tools for biological computation ([MIT License](https://github.com/biopython/biopython/blob/master/LICENSE.rst))
- [Plotly](https://plotly.com/python/) – Interactive graphing for Python ([MIT License](https://github.com/plotly/plotly.py/blob/master/LICENSE.txt))
- [Pandas](https://pandas.pydata.org/) – Data analysis and manipulation ([BSD License](https://github.com/pandas-dev/pandas/blob/main/LICENSE))
- [ipywidgets](https://ipywidgets.readthedocs.io/) – Interactive widgets in Jupyter ([BSD License](https://github.com/jupyter-widgets/ipywidgets/blob/main/LICENSE))
- [Kaleido](https://github.com/plotly/Kaleido) – Image export for Plotly figures ([MIT License](https://github.com/plotly/Kaleido/blob/master/LICENSE))

Special thanks to the open-source community for supporting reproducible science and free software development.

---

## 📃 License

MIT License – free to use, modify, and share.
