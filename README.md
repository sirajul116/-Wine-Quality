# -Wine-Quality
You have to upload the code into the Jupyter Notebook or google colab then upload the two dataset of red and white wine on it.

Code explanation:

Import Libraries: Firstly imported the important libraries in this section .

Read data: Here you can read the csv file. The code will work for two datasets. if you want to analysis the red wine then second line of read csv file should be comment out.
or if you want to analysis the white wine then comment out the first line of read csv file.

Data cleaning: 
1. here we first divided the dataset into colum.
2. remove the duplicate
3. checking and removing the nan values.
4.Convert the object data type to float64
5. then remove the outliers by IQR method

Data Visualization:
1. show the pie chart of avg value of every elemnet of wine
2. show the bar chart of avg value of every elemnet of wine
3. show the heatmap of every element of wine
4. show the satter plot of every elemnet vs quality of wine
