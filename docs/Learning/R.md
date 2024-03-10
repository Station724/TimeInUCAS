# R - Quick Guide [link](https://www.tutorialspoint.com/r/r_quick_guide.htm)



## 1. Data Type

```R
# Data Type
v <- TRUE               # logical
v <- 23.5               # numeric
v <- 2L                 # integer
v <- 2+5i               # complex
v <- "TRUE"             # character
v <- charToRaw("Hello") # raw


# Create a vector.(向量)
apple <- c('red','green',"yellow")


# Create a list.(列表)
list1 <- list(c(2,5,3),21.3,sin)


# Create a matrix.(矩阵)
M = matrix( c('a','a','b','c','b','a'), nrow = 2, ncol = 3, byrow = TRUE)


# Create an array.(阵列)
a <- array(c('green','yellow'),dim = c(3,3,2))


# Create a factor object.(因素)
apple_colors <- c('green','green','yellow','red','red','red','green')
factor_apple <- factor(apple_colors)


# Create the data frame. (数据框)
BMI <- 	data.frame(
   gender = c("Male", "Male","Female"), 
   height = c(152, 171.5, 165), 
   weight = c(81,93, 78),
   Age = c(42,38,26)
)
```

---



## 2. Variables

```R
# Variable Assignment
var.1 = c(0,1,2,3)       # equal
var.2 <- c("learn","R")  # leftward
c(TRUE,1) -> var.3       # rightward 


# Finding Variables
ls()                # List all variables in workspace
ls(pattern = "var") # List variables starting with the "var"
ls(all.name = TRUE) # list variables starting with dot(.) 


# Deleting Variables
rm(var.3)
rm(list = ls())
```

---



## 3. Operators

```R
# Arithmetic Operators(数学运算符)
v+t
v-t
v*t
v/t
v%%t   # remainder(余数)
v%/%t  # quotient(商，【被除数÷除数=商···余数】)
v^t


# Relational Operators(关系运算符)
v>t    # greater 
v<t    # less 
v == t # equal 
v<=t   # less than or equal
v>=t   # greater than or equal
v!=t   # unequal


# Logical Operators(逻辑运算符)
v&t   # Element-wise Logical AND(挨个比较向量元素)
v|t   # Element-wise Logical OR (挨个比较向量元素)
!v    # Logical NOT
v&&t  # Logical AND(仅考虑向量的第一个元素)
v||t  # Logical OR (仅考虑向量的第一个元素)


# Assignment Operators(赋值运算符)
v1 <- c(3,1,TRUE,2+3i)  
v2 <<- c(3,1,TRUE,2+3i)  
v3 = c(3,1,TRUE,2+3i)  # Left Assignment 
c(3,1,TRUE,2+3i) -> v1  
c(3,1,TRUE,2+3i) ->> v2 


# Miscellaneous Operators(混合运算符)
1:8      # [1] 1 2 3 4 5 6 7 8
t%in%v   # Is element 't' belongs to vector 'V'
M%*%t(M) # Multiply a matrix with its transpose
```

---



## 4. Decision making

```R
# If Statement
x <- 30L
if(is.integer(x)) {
   print("X is an Integer")
}


# If...Else Statement
x <- c("what","is","truth")
if("Truth" %in% x) {
   print("Truth is found")
} else {
   print("Truth is not found")
}


# Switch Statement (a little different)
x <- switch(3,
   "first",
   "second",
   "third",
   "fourth"
)
print(x)
```

---



## 5. Loops

```R

```















































