# Machine Learning Lab 5 – Face Clustering using K-Means

## Aim
The aim of this experiment was to perform clustering on face images using K-Means based on hue and saturation features extracted from images.

## Methodology
1. Face Detection:
- I used OpenCV’s cascade classifier to detect faces
  
2. Feature Extraction:
- I converted the images from BGR to HSV colour
- I extracted the features like hue and saturation values
- I calculated the mean hue and saturation for the detected face
  
3. Clustering:
- I applied K-Means clustering (k = 2) to each group
- I assigned each face to a cluster based on similarity
  
4. Hue and saturation were extracted
- The K-Means model predicted its cluster

5. Visualisation:
- I created a scatter plot of clusters
- centroids plotted
- template image plotted in predicted cluster

## Tools & Libraries
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## Results
### Cluster Visualisation


## Key Findings
- Faces were successfully clustered into two groups based on color features.
- Hue and saturation are useful features for basic image clustering.
- The template image was correctly assigned to one of the clusters.

## Conclusion
This lab demonstrated how K-Means clustering can be used for basic image classification tasks. It also showed how feature extraction plays an important role in machine learning models.
