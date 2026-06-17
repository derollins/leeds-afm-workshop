# AFM Image Analysis with Python Workshop

Resources and materials for the hands-on Python data handling workshop at the 2026 AFM & SPM conference in Leeds.

A hands-on workshop covering:

- loading AFM data
- batch processing pipelines for images and high-speed AFM videos
- analysis using Python
- exporting publication-quality results

---

## Setup Instructions

These instructions will guide you through setting up the Python environment needed to run the workshop notebooks.

---

### 1. Install Miniforge (recommended)

We recommend installing **Miniforge**, a lightweight Python/conda distribution that works well for scientific packages.

If you already have Miniforge, Anaconda, or Miniconda installed, you can skip this step.

Download it here:

https://conda-forge.org/download/

Follow the installation instructions for your operating system.

---

### 2. (Recommended) Install Git and create a GitHub account

We recommend installing **Git** and creating a free **GitHub account**.

This will allow you to:

- download the workshop materials easily
- keep your work backed up
- continue working with the notebooks after the workshop

#### Install Git

Download Git here:

https://git-scm.com/downloads

---

#### Create a GitHub account (if you don’t already have one)

https://github.com/

---

#### Check Git is installed

Open a terminal (or command prompt on Windows) and run:

```bash
git --version
```

---

### 3. Download the workshop materials

```bash
git clone https://github.com/derollins/leeds-afm-workshop.git
cd leeds-afm-workshop
```

Or without Git:

- Go to: https://github.com/derollins/leeds-afm-workshop
- Click **Code → Download ZIP**
- Extract the folder and open it in a terminal

---

### 4. Create the Python environment

In the project folder, run:

```bash
conda env create -f environment.yml
```

This will install all required packages (this may take a few minutes).

---

### 5. Activate the environment

```bash
conda activate leeds_python_workshop
```

---

### 6. Launch Jupyter

```bash
jupyter lab
```

(or use `jupyter notebook` if you prefer)

---

### 7. Open the workshop notebooks

Navigate to the `notebooks/` folder and start with:

```txt
00_intro.ipynb
```

Then work through the notebooks in order:

1. `01_loading.ipynb`
2. `02_processing.ipynb`
3. `03_analysis.ipynb`
4. `04_export.ipynb`

---

## Troubleshooting

### `conda` not recognised

Try running:

```bash
conda init
```

Then restart your terminal.

---

### Environment creation fails

Try updating conda:

```bash
conda update conda
```

Then rerun:

```bash
conda env create -f environment.yml
```

---

### Jupyter won’t start

Try:

```bash
python -m jupyter lab
```

---

## 💡 Tips

- Please install everything **before the workshop** to save time
- If something breaks, don’t worry — we’ll help troubleshoot during the session
