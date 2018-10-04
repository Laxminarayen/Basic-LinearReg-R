# Basic-R
data("longley")
str(longley)
model1 <- lm(GNP~.,longley[,-c(5,6,7)])
summary(model1)
