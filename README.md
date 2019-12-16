# Reading and writing CSV data

1 #
First, I created a variable, df, with the value "as.data.frame (read ..)" to read the csv file as a data frame.

2 #
I used the head () function with n =? option to print a specified number of lines (number of lines showing = n) from my data frame. I calculate the value n in a simple way: using half the number of lines.

3 #
I created the variables "names", "age" and "class" and then created a dataframe with the data.frame () function.

4 #
I created a new variable called 'height' with height values for each person in 'df'. Then I created 'newdf' with a new column: 'height'. The 'height' column was associated to df from the cbind function(). After that, I created the "lastrow" variable which is a data.frame with the same variables, but only one obs.(the one that I'll add to "newdf") Using rbind() function I created the "newnewdf" that aggregate the "lastrow" variable with "newdf" dataframe.

5#
I just used the write.csv () function to write a csv file, "student.csv". The first parameter of the function is the data frame and the second is where and how the file to be saved will be called. So "write.csv(newnewdf,'students.csv')"
the file will be created from "newnewdf" data frame and saved in the directory where you are working with "students" name.

6#
For this question I used the "students.csv" file from my github repository, so I only read it...then I done the same of my 3# resolution.
