# 3D Shape Retrieval System

## Overview
This project is a **Content-Based 3D Shape Retrieval System** designed to process 3D mesh files, extract descriptive features, and retrieve the most similar shapes from a large database. The system enables users to visualize 3D shapes, preprocess them for consistency, extract meaningful features, and execute shape-based queries efficiently.

The assignment follows a structured approach, focusing on implementing foundational steps first and building up to a fully functional retrieval system.

---
## Project Structure

- **`database/`**  
  Contains the database of 3D mesh files used for querying and analysis.

- **`statistics/`**  
  Stores all the statistics and metrics computed from the data throughout the project.

- **`templates/`**  
  Houses the templates for the interactive Graphical User Interface (GUI).

- **`query/`**  
  Saves the history of query meshes used in the retrieval process.

- **`Final_Version.ipynb`**  
  The main project code implemented in a Jupyter Notebook.

- **`req.txt`**  
  A list of all required Python dependencies for the project.

## Features
1. **3D Shape Viewer**  
   - Visualize 3D shapes with interactive controls for zooming, rotating, and panning.
   
2. **Shape Preprocessing**  
   - Compute basic statistics like vertex/face count and bounding box dimensions.
   - Normalize shapes through translation, scaling, alignment, and flipping.
   - Identify and resample poorly meshed shapes.

3. **Feature Extraction**  
   - Extract various 3D descriptors, including global and histogram-based features:
     - Surface Area, Compactness, Rectangularity, Convexity, etc.
     - Distributions such as A3, D1, D2, D3, and D4.

4. **Querying**  
   - Compare a query shape against the database using normalized features.
   - Use distance metrics (e.g., Euclidean) to retrieve the most similar shapes.
   - Visualize the top-K results.

5. **Scalability**  
   - Optimize for performance when working with large shape databases.

6. **Evaluation**  
   - Evaluate the system using various metrics like precision, recall, F1-score, and accuracy.

---

## Getting Started

### Prerequisites
Before running the project, ensure you have the following installed:
- **Python 3.8+**
- Required Python libraries (listed in `req.txt`).
- 3D shape datasets in OBJ or PLY format.

### Setup Instructions for Using the GUI (Steps 4 and 5): Replace NGROK Token
After running the first cell (which includes the necessary imports for the project), replace the NGROK token with your own. This step is required to ensure the project runs correctly on your machine.

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
2. Install required Python libraries:
   ```bash
   pip install -r req.txt
   ```


## Project Report
- `Multimedia_Retrieval_2024_Panagiotis_Andrikopoulos_Stylianos_Psara_Ziv_Hochman.pdf`: The project report contains detailed descriptions of all the steps outlined in the implementation section, including objectives, results, and conclusions.























