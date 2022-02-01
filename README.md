# PySpark_Assignment_Group-6

The dataset used for the assignment is [Movie-Dataset-Latest.csv](https://github.com/keerthana99/PySpark_Assignment_Group-6/blob/dc0ceb8b41d01327bcf3187560edbc47496c0439/Movie-Dataset-Latest.csv).

[Entertainment- movie.ipynb](https://github.com/keerthana99/PySpark_Assignment_Group-6/blob/87dc38b2c4b5cc4e4c1d26d9f9e152a3823a4866/Entertainment-%20movie.ipynb) is the pyspark code implemented in Jupyter Notebook.

[vote_avg_count.csv](https://github.com/keerthana99/PySpark_Assignment_Group-6/blob/e0bfd16a8fcabf7c58372e582e988c8aa9a47dc4/vote_avg_count.csv) is the output after doing groupby and count on the vote_average variable.
 
 [Output.txt](https://github.com/keerthana99/PySpark_Assignment_Group-6/blob/589b0e17f0daf5d7b73f6435c6d06c7f17d10fed/Output.txt) is the output file in txt format.
  
## The assignment contains following operations.

i.Extract:  Load the data
   
   - Read data as csv via spark dataframe

ii.Transform: Exploratory data analysis using spark df
    
   - Unique id count
   
   - split column release_date into three columns -> year,month and day
   
   - Replace - month -> 1 to Jan and 2 to Feb and so on
   
   - Update : Normalize popularity column - normalized  v = v - min(popularity)/max(popularity)-min(popularity)
   
   - remove - overview and video column
   
   - show df
   
   - GroupBy vote_average and count

iii.Load: Save analysis report
    
   - show df, save as files


## Group 6 members
 
 SARAH MERIN JOHN - 20BDA06
 
 MANU TOM - 20BDA23
 
 KEERTHANA SAJEEVAN - 20BDA39
 
 TONMOY DUTTA - 20BDA57
 
 ANANYA KUMARI - 20BDA68
