# IonVision  

IonVision is a Python package developed by the trapped ion team at the National Quantum Computing Centre (NQCC). It enables automated rendering of energy-level diagrams and generation of pulse-sequence timelines for trapped-ion quantum computing experiments.  


Cloning and Running the Repository

# 1. Clone the repository

Clone the repository to your local machine:

git clone [<repository-url>](https://github.com/stfc/IonVision)
cd <repository-folder>
# 2. Create and activate a virtual environment (recommended)
python -m venv venv
source venv/bin/activate

On Windows:

venv\Scripts\activate
# 3. Install the required dependencies
pip install -r requirements.txt
Viewing the Documentation with MkDocs

This repository uses MkDocs to build and preview the documentation.

# 4. Install MkDocs (if not already installed)
pip install mkdocs

If the project uses a theme such as Material for MkDocs, install it as well:

pip install mkdocs-material

# 5. Serve the documentation locally

From the root of the repository, run:

mkdocs serve
# 6. View the documentation

Once the server starts, open a browser and go to:

http://127.0.0.1:8000

The site will automatically reload whenever you modify the documentation files.

