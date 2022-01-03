# imt
Image Management Tool - Python based tool for image data management

The tool allows to modify, sort and filter image data interactively. 
Input is a folder of images that should be modified, filtered or sorted and an optional pandas dataframe.

Output is a folder of images that are sorted, modified or filtered. The visualization happens purely on 
basis of the 

## Requirements

```
click
pandas
PIL
```



## Functions
1. Change Resolution, Extension and Name
2. Sort by Luminance, Coloraxis, Extracted Features, PCA
3. Filter according to Pandas Dataframe
