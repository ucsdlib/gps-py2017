

```python
!ls *py
```

    analyze_mosquitos.py



```python
%matplotlib inline
```

* you can import modules just like you can other libraries 
* as long as they are 


```python
import analyze_mosquitos
```


```python
data = analyze_mosquitos.create_mosquitos_vs_tempC_plot("data/A2_mosquito_data.csv")
```

    Loading data/A2_mosquito_data.csv
    Plotting data/A2_mosquito_data.csv
    Saving data/A2_mosquito_data_mosquitos_vs_tempC.png



![png](output_4_1.png)



```python
!ls -l *.png
```

    -rw-r--r--  1 jtdennis  2113415076  6814 Feb  7 14:42 A1_mosquito_data_mosquitos_vs_tempC.png



```python
analyze_mosquitos.create_mosquitos_vs_tempC_plot?
```

### In class challenge

* Write a for loop to do the above
* use glob for grabbing a list of files


```python

```
