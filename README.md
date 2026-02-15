# Lab-5
# Face Detection Assignment

## Aim
The aim of this assignment is to understand how face detection works using computer vision techniques.  
We detect faces from input images, analyze their spatial features, and visualize the results using plots and graphs to better understand the impact of face insertion on the data.

## Methodology
- Used Python and OpenCV to detect faces in images.
- Extracted bounding box information such as x-coordinate, y-coordinate, width, and height of detected faces.
- Plotted the face features using scatter plots to observe patterns.
- Compared visualizations **before inserting faces** and **after inserting faces** to analyze the change.
- Applied clustering to group similar face detections and visualize them clearly.

## Visualisations

### 1. Before Face Insertion
The following graph shows the data distribution before any face was inserted into the image.  
This helps establish a baseline for comparison.
<img width="1052" height="569" alt="image" src="https://github.com/user-attachments/assets/f6818968-7e9b-46b7-ab4f-f483085e9947" />

### 2. After Face Insertion
This graph shows the updated distribution after faces were inserted and detected.  
We can clearly observe changes in the data pattern compared to the previous plot.
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/22df93a8-def1-47d4-9cbf-6d76b919d729" />

## Key Findings
- Face insertion significantly changes the spatial distribution of detected features.
- After insertion, more structured patterns appear in the plots.
- Clustering helps in grouping faces with similar bounding box properties.
- Visual comparison makes it easier to understand the effect of face detection on image data

## Conclusion
Through this assignment, I gained hands-on experience with face detection using OpenCV and data visualization using Python.  
The comparison between pre-insertion and post-insertion graphs clearly demonstrates how face detection alters feature distributions.  
Overall, this assignment helped strengthen my understanding of computer vision workflows and analytical interpretation of visual data.

## How to Run the Notebook
1. Open the `.ipynb` file in Jupyter Notebook or VS Code.
2. Run all cells in order.
3. Ensure required Python libraries such as OpenCV, NumPy, and Matplotlib are installed.
