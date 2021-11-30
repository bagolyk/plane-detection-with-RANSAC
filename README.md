# Plane Detection with Sequential RANSAC

Assignment for 3D Computer Vision class at ELTE Autonomous Systems MSc
2021

## Assignment description

Implement the Sequential RANSAC (SeqRANSAC) algorithm with optimal plane detection. The method for optimal plane detection is overviewed in the lecture on 27th September, you can find the details hereLinks to an external site.. Find the three most dominant planes by SeqRANSAC. Try to tune the RANSAC parameter to find good planes, however, do not worry if the detection is not perfect. Run the method on all the data. Upload the source codes and the results in PLY format (coloured point clouds) to Canvas. Colour the three detected planes by red, green and pink.

 Sequential RANSAC is the iterative modification of RANSAC: it finds a plane by RANSAC, then the plane points are removed from the dataset, and RANSAC method is run again on the rest of the points. The plane detection and removal can be iterated many times. In this assignment, the three most dominant plane should be found. 

## Visualizing some results

### Result for Tunnel pointcloud
![image](https://user-images.githubusercontent.com/43494568/144138065-de4253c5-c2a7-4d33-b6f5-136095fc7ad9.png)
![image](https://user-images.githubusercontent.com/43494568/144138117-9d1c9b40-935d-4d89-b0fd-4ed20c75dbbd.png)

### Result for BeforeCross pointcloud
![image](https://user-images.githubusercontent.com/43494568/144138174-9a7ed909-640b-4bb4-bfde-f926a42390fd.png)

### Result for ChainBridge pointcloud
![image](https://user-images.githubusercontent.com/43494568/144138250-8fdcd233-bfcd-4bfd-949b-63aca09dbf28.png)

### Result for Dense pointcloud
![image](https://user-images.githubusercontent.com/43494568/144138348-9299617a-d6e5-4191-a77c-473d7d3f15da.png)
![image](https://user-images.githubusercontent.com/43494568/144138381-2b1102b0-8c4e-49ae-a904-76b8b366d310.png)
