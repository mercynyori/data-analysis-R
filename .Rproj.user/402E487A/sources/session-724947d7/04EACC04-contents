StudentsPerformanceDataset <- read.csv("C:/Users/hp/Downloads/StudentsPerformance_with_headers.csv", header=TRUE)
library("psych")
describe(StudentsPerformanceDataset)
hist(StudentsPerformanceDataset$Student.Age)
hist(StudentsPerformanceDataset$Weekly.study.hours)
hist(StudentsPerformanceDataset$Sex)
hist(StudentsPerformanceDataset$Attendance.to.classes)
hist(StudentsPerformanceDataset$GRADE)
head(StudentsPerformanceDataset)
dim(StudentsPerformanceDataset)
StudentsPerformanceDataset[is.na(StudentsPerformanceDataset)]
boxplot(StudentsPerformanceDataset$GRADE)
boxplot(StudentsPerformanceDataset$Weekly.study.hours)
boxplot(StudentsPerformanceDataset$Do.you.have.a.partner)
duplicated(StudentsPerformanceDataset)
set.seed(42)
my_clean<- StudentsPerformanceDataset %>% select(Weekly.study.hours, Do.you.have.a.partner,Taking.notes.in.classes, GRADE)
View(my_clean)
my_sample <- my_clean %>% slice_sample(n = 100)
View(my_sample)


# -------------------------------------------------------------------------



