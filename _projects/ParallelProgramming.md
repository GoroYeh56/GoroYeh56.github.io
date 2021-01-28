---
title: "Parallel Programming - Projects"
excerpt: "Course project of Parallel Programming <br/><img src='/images/graph_v28.gif' style='margin-left:15%' >"
collection: projects
---


## HW1 : Odd - Even Sort
![Odd-Even Sort image](https://github.com/GoroYeh56/images/illustration.png)  

* Use **MPI** to complete odd-even sort across different processes.  
[Github repository - OddEvenSort](https://github.com/GoroYeh56/Odd_Even_Sort---Parallel_Programming)


## HW2 : Mandelbrot Set
![Mandelbrot Set image](https://github.com/GoroYeh56/images/mandelbrot_fast.png)  
* Increase the computation time of sequential Mandelbrot Set using **Dynamic Load Balancing** and **Vectorization.**
* Complete with two version: 
  2a : Pthread only
  2b : Hybrid with MPI and OpenMP

* **Ranked 5th out of 64 students** in the class
* Handcrafted dynamic task assignment with Master and Slave workpool using MPI Send() and Recv().  
[Github repository - Mandelbrot Set](https://github.com/GoroYeh56/Mandelbrot_Set---Parallel_Programming)


## HW3 : All-Pair Shortest Path (CPU version)  
* [Spec](https://apollo.cs.nthu.edu.tw/pp20/hw3/) 
* Number of Vertices: from 2 to  6000  
* Number of Edges: from 0 to  V*(V-1)  
![HW3 image](https://github.com/GoroYeh56/images/APSP.png)  
[Github repository - hw3-PP](https://github.com/GoroYeh56/AllPairsShortestPath--ParallelProgramming)

## HW4-1: Block All-Pair Shortest Path (GPU CUDA version)
* [Spec](https://apollo.cs.nthu.edu.tw/pp20/hw4-1/#input-output-format)  
* Number of Vertices: from 2 to  40000    
* Number of Edges: from 0 to  V*(V-1)  
![Blocked APSP](https://github.com/GoroYeh56/images/BlockedAPSP_illus.PNG)  
![Blocked APSP-3phases](https://github.com/GoroYeh56/images/BlockedAPSP_3phases.PNG)  
## HW4-2: Block All-Pair Shortest Path (Multi-GPU version)  
* [Spec](https://apollo.cs.nthu.edu.tw/pp20/hw4-2/)  
* Number of Vertices: from 2 to  60000    
* Number of Edges: from 0 to  V*(V-1)  
<!-- ![Blocked APSP Multi-GPU]()   -->
[Github repository - hw4](https://github.com/GoroYeh56/AllPairsShortestPath_CUDA--ParallelProgramming)

## Final Project: Parallelize RRT* 

* Parallelize sequential version RRT and RRT* algorithms.  

<img src="/images/graph_v3001.gif" alt="RRT-gif" width="350"/><img src="/images/graph_v28.gif" alt="RRT*-gif" width="350"/> 

<img src="/images/graph_v301_start.png" alt="RRT start" width="350"/><img src="/images/graph_v101.png" alt="RRT end" width="350"/> 

<img src="/images/graph_v28_start.png" alt="RRT* start" width="350"/><img src="/images/graph_v28.png" alt="RRT* end" width="350"/> 

[Presentation Slide](https://drive.google.com/file/d/1Ohf34b0meSxq7hLQwcmtsyY3wBlIOINA/view?usp=sharing)

[Github repository - RRT*-PPFinal](https://github.com/GoroYeh56/RRTstar_Parallel-Programming)
