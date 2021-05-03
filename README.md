# assi5
data <- read.csv("data.csv")
print(data)
result.mean <- mean(data['age'])
print(result.mean)
result.mean <- mean(data['age',na.rm = TRUE)
print(result.mean)
median.result <- median(data['age'])
print(median.result)
result <- getmode(data['age'])
print(result)
#sd
sd(c(data['age'],na.rm = TRUE))
x <- c(1, 2, 3)
sqrt(mean(x ^ 2) - mean(x)^2)
n <- length(x) 
std <- sd(x) 
sqrt((std ^ 2) * ((n - 1) / n))
#min
x <-c(data['age'])
min(x)
#max
x <-c(data['age'])
max(x)
output:
mean:38.22
median:22.33
mode:33
standard deviation: 0.9856413
min : 22
max : 45
