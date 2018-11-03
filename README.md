# mlcourse 

## Topic3 Decision Tree 

### Information Gain

-  <a href="https://www.codecogs.com/eqnedit.php?latex=S&space;=&space;-\sum_{i=1}^{N}p_i*log_2{p_i}" target="_blank">Shannon's entropy<img src="https://latex.codecogs.com/gif.latex?S&space;=&space;-\sum_{i=1}^{N}p_i*log_2{p_i}" title="S = -\sum_{i=1}^{N}p_i*log_2{p_i}" /></a>


- <a href="https://www.codecogs.com/eqnedit.php?latex=IG&space;=&space;S_0-&space;\sum_{i=1}^q\frac{N_i}{N}S_i" target="_blank">information gain <img src="https://latex.codecogs.com/gif.latex?IG&space;=&space;S_0-&space;\sum_{i=1}^q\frac{N_i}{N}S_i" title="IG = S_0- \sum_{i=1}^q\frac{N_i}{N}S_i" /></a>

the process of finding the optimal feature and threshold
```
for loop:
	for each feature:
		caculate the IG
	find the optimal feature and threshold

```




