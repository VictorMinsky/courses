# R Programming (JHU) Quiz 1
#### *Here is a complete collection of all the answers.

Question 1
----------
R was developed by statisticians working at:

- [x] The University of Auckland
- [ ] Bell Labs
- [ ] StatSci
- [ ] Insightful
- [ ] Johns Hopkins University
- [ ] Harvard University
- [ ] The University of New South Wales

**Explanation:**<br>
*The R language was developed by Ross Ihaka and Robert Gentleman who were statisticians at the University of Auckland in New Zealand.*

Question 2
----------
The R language is a dialect of which of the following programming languages?

- [x] S
- [ ] Haskell
- [ ] C
- [ ] Java

**Explanation:**<br>
*R is a dialect of the S language which was developed at Bell Labs*

Question 3
----------
The definition of free software consists of four freedoms (freedoms 0 through 3). Which of the following is NOT one of the freedoms that are part of the definition? Select all that apply.

- [x] The freedom to prevent users from using the software for undesirable purposes.
- [x] The freedom to sell the software for any price.
- [x] The freedom to restrict access to the source code for the software.
- [ ] The freedom to improve the program, and release your improvements to the public, so that the whole community benefits.
- [ ] The freedom to redistribute copies so you can help your neighbor.
- [ ] The freedom to study how the program works, and adapt it to your needs.
- [ ] The freedom to run the program, for any purpose.

**Explanation:**<br>
*1. This is not part of the free software definition. Freedom 0 requires that the users of free software be free to use the software for any purpose.*<br>
*2. This is not part of the free software definition. The free software definition does not mention anything about selling software (although it does not disallow it).*<br>
*3. This is not part of the free software definition. Freedoms 1 and 3 require access to the source code.*

Question 4
----------
In R the following are all atomic data types EXCEPT: (Select all that apply):

- [x] table
- [x] array
- [x] list
- [x] matrix
- [x] data frame
- [ ] complex
- [ ] logical
- [ ] integer
- [ ] character
- [ ] numeric

**Explanation:**<br>
*1. 'table' is not an atomic data type in R.*<br>
*2. 'array' is not an atomic data type in R.*<br>
*3. 'list' is not an atomic data type in R.*<br>
*4. 'matrix' is not an atomic data type in R.*<br>
*5. 'data frame' is not an atomic data type in R.*

Question 5
----------
If I execute the expression x <- 4 in R, what is the class of the object 'x' as determined by the 'class()' function?

- [x] numeric
- [ ] vector
- [ ] real
- [ ] list
- [ ] integer
- [ ] complex
- [ ] matrix

Question 6
----------
If I execute the expression x <- 4L in R, what is the class of the object 'x' as determined by the 'class()' function?

- [x] integer
- [ ] character
- [ ] complex
- [ ] numeric
- [ ] logical
- [ ] matrix

**Explanation:**<br>
*The 'L' suffix creates an integer vector as opposed to a numeric vector.*

Question 7
----------
What is the class of the object defined by x <- c(4, TRUE)?

- [x] numeric
- [ ] integer
- [ ] character
- [ ] logical
- [ ] list
- [ ] matrix

**Explanation:**<br>
*The numeric class is the "lowest common denominator" here and so all elements will be coerced into that class.*

Question 8
----------
What is the class of the object defined by the expression x <- c(4, "a", TRUE)?

- [x] character
- [ ] logical
- [ ] numeric
- [ ] mixed 
- [ ] integer

**Explanation:**<br>
*The character class is the "lowest common denominator" here and so all elements will be coerced into that class.*

Question 9
----------
If I have two vectors x <- c(1,3, 5) and y <- c(3, 2, 10), what is produced by the expression rbind(x, y)?

- [x] a matrix with two rows and three columns
- [ ] a 3 by 2 matrix
- [ ] a 3 by 3 matrix
- [ ] a vector of length 3
- [ ] a vector of length 2
- [ ] a 2 by 2 matrix

**Explanation:**<br>
*The 'rbind' function treats vectors as if they were rows of a matrix. It then takes those vectors and binds them together row-wise to create a matrix.*

Question 10
----------
If I have two vectors x <- c(1,3, 5) and y <- c(3, 2, 10), what is produced by the expression cbind(x, y)?

- [x] a matrix with 2 columns and 3 rows
- [ ] a 2 by 3 matrix
- [ ] a vector of length 3
- [ ] a 2 by 2 matrix
- [ ] a vector of length 2
- [ ] a 3 by 3 matrix

**Explanation:**<br>
*The 'cbind' function treats vectors as if they were columns of a matrix. It then takes those vectors and binds them together column-wise to create a matrix.*

Question 11
----------
A key property of vectors in R is that:

- [x] elements of a vector all must be of the same class
- [ ] a vector cannot have have attributes like dimensions
- [ ] the length of a vector must be less than 32,768
- [ ] elements of a vector can only be character or numeric
- [ ] elements of a vector can be of different classes

Question 12
----------
Suppose I have a list defined as x <- list(2, "a", "b", TRUE). What does x[[2]] give me? Select all that apply.

- [x] a character vector of length 1.
- [x] a character vector containing the letter "a".
- [ ] a list containing a character vector with the elements "a" and "b".
- [ ] a list containing character vector with the letter "a".
- [ ] a character vector with the elements "a" and "b".

Question 13
----------
Suppose I have a list defined as x <- list(2, "a", "b", TRUE). What does x[[1]] give me? Select all that apply.

- [x] a numeric vector containing the element 2.
- [x] a numeric vector of length 1.
- [ ] a character vector containing the element "2".
- [ ] a list containing a numeric vector of length 1.
- [ ] a list containing the number 2.

Question 14
----------
Suppose I have a vector x <- 1:4 and y <- 2:3. What is produced by the expression x + y?

- [x] an integer vector with the values 3, 5, 5, 7.
- [ ] an numeric vector with the values 3, 5, 5, 7.
- [ ] a numeric vector with the values 1, 2, 5, 7.
- [ ] a warning
- [ ] an error.
- [ ] an integer vector with the values 3, 5, 3, 4.
- [ ] a numeric vector with the values 3, 5, 3, 4.

Question 15
----------
Suppose I have a vector x <- 1:4 and a vector y <- 2. What is produced by the expression x + y?

- [x] a numeric vector with elements 3, 4, 5, 6.
- [ ] a numeric vector with elements 3, 2, 3, 6.
- [ ] an integer vector with elements 3, 2, 3, 4.
- [ ] a numeric vector with elements 1, 2, 3, 6.
- [ ] an integer vector with elements 3, 2, 3, 6.
- [ ] a numeric vector with elements 3, 2, 3, 4.

Question 16
----------
Suppose I have a vector x <- c(17, 14, 4, 5, 13, 12, 10) and I want to set all elements of this vector that are greater than 10 to be equal to 4. What R code achieves this? Select all that apply.

- [x] x[x >= 11] <- 4
- [x] x[x > 10] <- 4
- [ ] x[x < 10] <- 4
- [ ] x[x > 4] <- 10
- [ ] x[x >= 10] <- 4
- [ ] x[x == 4] > 10
- [ ] x[x > 10] == 4
- [ ] x[x == 10] <- 4

**Explanation:**<br>
*1. You can create a logical vector with the expression x >= 11 and then use the [ operator to subset the original vector x.*<br>
*2. You can create a logical vector with the expression x > 10 and then use the [ operator to subset the original vector x.*

Question 17
----------
Suppose I have a vector x <- c(3, 5, 1, 10, 12, 6) and I want to set all elements of this vector that are less than 6 to be equal to zero. What R code achieves this? Select all that apply.

- [x] x[x < 6] <- 0
- [x] x[x %in% 1:5] <- 0
- [x] x[x <= 5] <- 0
- [ ] x[x == 6] <- 0
- [ ] x[x > 0] <- 6
- [ ] x[x < 6] == 0
- [ ] x[x > 6] <- 0
- [ ] x[x != 6] <- 0
- [ ] x[x >= 6] <- 0
- [ ] x[x == 0] < 6
- [ ] x[x == 0] <- 6

**Explanation:**<br>
*1. You can create a logical vector with the expression x < 6 and then use the [ operator to subset the original vector x.*<br>
*2. You can create a logical vector with the expression x %in% 1:5 and then use the [ operator to subset the original vector x.*<br>
*3. You can create a logical vector with the expression x <= 5 and then use the [ operator to subset the original vector x.*

Question 18
----------
Use the [Week 1 Quiz Data Set](https://d396qusza40orc.cloudfront.net/rprog/data/quiz1_data.zip) to answer questions 11-20.

In the dataset provided for this Quiz, what are the column names of the dataset?

- [x] Ozone, Solar.R, Wind, Temp, Month, Day
- [ ] Ozone, Solar.R, Wind
- [ ] Month, Day, Temp, Wind
- [ ] 1, 2, 3, 4, 5, 6

**Explanation:**<br>
*You can get the column names of a data frame with the 'names()' function.*

Question 19
----------
Extract the first 2 rows of the data frame and print them to the console. What does the output look like?

- [x] Answer:
```
   Ozone Solar.R Wind Temp Month Day
1    41     190  7.4   67     5   1
2    36     118  8.0   72     5   2 
```

**Explanation:**<br>
*You can extract the first two rows using the [ operator and an integer sequence to index the rows.*

Question 20
----------
How many observations (i.e. rows) are in this data frame?

- [x] 153
- [ ] 160
- [ ] 129
- [ ] 45

**Explanation:**<br>
*You can use the 'nrows()' function to compute the number of rows in a data frame.*

Question 21
----------
Extract the last 2 rows of the data frame and print them to the console. What does the output look like?

- [x] Answer:
```
   Ozone Solar.R Wind Temp Month Day
 1    41     190  7.4   67     5   1
 2    36     118  8.0   72     5   2
```

**Explanation:**<br>
*The 'tail()' function is an easy way to extract the last few elements of an R object.*

Question 22
----------
What is the value of Ozone in the 47th row?

- [x] 21
- [ ] 18
- [ ] 63
- [ ] 34

**Explanation:**<br>
*The single bracket [ operator can be used to extract individual rows of a data frame.*

Question 23
----------
How many missing values are in the Ozone column of this data frame?

- [x] 37 
- [ ] 43
- [ ] 9
- [ ] 78

**Explanation:**<br>
*The 'is.na' function can be used to test for missing values.*

Question 24
----------
What is the mean of the Ozone column in this dataset? Exclude missing values (coded as NA) from this calculation.

- [x] 42.1
- [ ] 31.5
- [ ] 18.0
- [ ] 53.2

**Explanation:**<br>
*The 'mean' function can be used to calculate the mean.*

Question 25
----------
Extract the subset of rows of the data frame where Ozone values are above 31 and Temp values are above 90. What is the mean of Solar.R in this subset?

- [x] 212.8
- [ ] 205.0
- [ ] 334.0
- [ ] 185.9

**Explanation:**<br>
*You need to construct a logical vector in R to match the question's requirements. Then use that logical vector to subset the data frame.*

Question 26
----------
What is the mean of "Temp" when "Month" is equal to 6?

- [x] 79.1
- [ ] 90.2
- [ ] 85.6
- [ ] 75.3

Question 27
----------
What was the maximum ozone value in the month of May (i.e. Month is equal to 5)?

- [x] 115
- [ ] 18
- [ ] 97
- [ ] 100

