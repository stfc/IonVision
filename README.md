# IonVision

IonVision is a Python package developed by the trapped ion team at the National Quantum Computing Centre (NQCC). It enables automated rendering of energy-level diagrams and generation of pulse-sequence timelines for trapped-ion quantum computing experiments.

---

## Getting Started

### 1. Clone the repository

Clone the repository to your local machine:

```bash
git clone https://github.com/stfc/IonVision
cd IonVision
```

---

### 2. Create and activate a virtual environment (recommended)

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on **macOS/Linux**:

```bash
source venv/bin/activate
```

Activate it on **Windows**:

```bash
venv\Scripts\activate
```

---

### 3. Install the required dependencies

Install the project dependencies:

```bash
pip install -r requirements.txt
```

---

## Viewing the Documentation

This repository uses **MkDocs** to build and preview the documentation.

### 4. Install MkDocs (if not already installed)

```bash
pip install mkdocs
```

If the project uses the Material theme:

```bash
pip install mkdocs-material
```

---

### 5. Serve the documentation locally

From the root of the repository, run:

```bash
mkdocs serve
```

---

### 6. View the documentation

Once the server starts, open your browser and go to:

```
http://127.0.0.1:8000
```

The documentation site will automatically reload whenever you modify the documentation files.