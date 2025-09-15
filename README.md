# Quizzes-2---Chloe-LaForge
Copy of R Studio for Lab 1

#Initial Questions
x <- 5
typeof(x)

x<- "a"

typeof(x)

x <- c(2, 2, 4, 5, 7, 10, 11, 9, 10)

print(x[5])

x<- c(1,2,3,4,5)

for(i in x){
  print(i)



  convert_to_celsius <- function(fahrenheit) {
    return((fahrenheit - 32) * 5/9)
  }
  
x <- 3
y <- 5
sum2 <-function(x,y){
  return(x+y)
  }

sum2(x,y)

#Q16
x <- 1:5
for(i in x)
  print(i*i)

#Q19-Q22
setwd("~/Desktop/SYS - Data/iris.txt")
iris <- read.csv("iris.txt", header = TRUE)

summary(iris)

iris[2,3]

iris$petal.length[2]

iris[ , "sepal.length"]
iris[["sepal.length"]]
iris[1, "sepal.length"]  
iris[[1]]
iris[, 1]
iris[1]

iris[10:20, ]

