# tsp_solver

Solves a tsp problem. The solution graphically displays the coordinates, then connects them. The program starts by connecting the first three "cities" then it finds the next closest city and adds it to the travelling salesman's route, one by one, until all the cities have been included into the route. 

Text files have been included -containing coordinate data- so you can test different maps out; Change the text file on line 49 of the TSPMap.py module, the text files are in the map_files directory.

Also change the path to the text file to match the path on your computer where the text file resides.

To get the module running in bash:<br />
```bash
$ python main.py
```

In Idle:<br />
```
file->open (main.py)->run
```

In Idle from the prompts:<br />
```idle
>>> import os
>>> os.popen('python main.py')
```



### Files:

main.py:<br />
	runs the program

TSPMap.py:<br />
	The algorithm focuses on preventing lines from crossing and <br /> by focusing on reducing total calculations. This is done <br /> by using various geometric functions.
            
tspturtle.py:<br />
	Uses turtle to display the output graphically.

matrix.py:<br />
	Solves a 2 by 3 matrix.

---------------------------------------------------------------
