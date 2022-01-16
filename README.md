# Algorithm Visualizer
Animated pathfinding visualization of algorithms using tkinter and pygame

## Project Description
We aim to visualize basic pathfinding algorithms i.e. **Dijkstra's algorithm, breadth-first search algorithm (BFS) and A* algorithm** by not only using path blockers (walls) but also finding its way through customized mazes. 

## Working

* Initial setup on running python `main.py`

![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/1.png)

  The Menu on the left shows the algorithms to select from along with the instructions on how to proceed.
  The grid on the right is where the visualisation will take place. Every block is a node of equal weight.

* Using custom made walls by selecting `walls` option and dragging mouse to make desired structure

![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/9.png)

* Selecting start and end positions

  The start point and the end point are representated by green and red colors respectively.

* Visualizing Dijkstra’s
![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/10.png)
  As the algorithm traverses through the nodes, the color gradually changes from shades of purple to blue. This helps in examining the order in which they were traversed.

* After pathfinding is complete
![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/11.png)
  The green path is the shortest path found by the system.

* Similarly, visualizing path for A*
![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/12.png)


* Similarly, visualizing path for BFS 
![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/13.png)


* Auto generated maze after clicking on `generate maze`
![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/2.png)
  Click on `clear grid` to return to initial setup and generate a custom maze.

* Selecting start and end points
![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/3.png)

* Visualizing and finding path for Dijkstra’s
![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/5.png)

* Similarly, visualizing and finding path for A*
![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/6.png)

* Similarly, visualizing and finding path for BFS
![](https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/7.png)

* Settings window to change visualiser window dimensions, number of squares in grid, animation speed, etc
<img src="https://github.com/kritanjalijain/algorithm_visualizer/blob/main/images/15.png" height= 500 width=300 align=center>

## Built With
* Languages - python
* GUI Library - Tkinter

## Setup and Installation
* Clone the repository 
``` 
git clone https://github.com/kritanjalijain/algorithm_visualizer.git
```
* Change to working directory
```
cd algorithm_visualizer
```
* Install all dependencies (preferrably in a virtual env)
```
pip install -r requirements.txt
```
* Run the program by running main
```
python main.py
```


