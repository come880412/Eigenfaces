# Eigenfaces
- This is the course of NTU 2021fall DLCV hw0
# My method
- First, I use Singular Value Decompsition(SVD) to find the most important eigenvectors. And, plot the top-4 eigenfaces and the mean face below.

![Eigenfaces](https://user-images.githubusercontent.com/59093784/138810855-2e0d419f-8de7-4b77-be06-97c5bc01973a.jpg)
- Next, I use these eigenfaces to reconstruct the face.
![reconstrunction](https://user-images.githubusercontent.com/59093784/138810974-e9c552eb-3f81-4f9f-a9e1-3052d3e1066b.jpg)
Where n is the number of eigenfaces I use to reconstruct the face.

- After that, I use K_Nearest_Neighbor(KNN) algorithm to do face recognition.

