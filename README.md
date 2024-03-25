
airquality 

head(airquality)
data_air<-data.frame(airquality)
data_air
str(data_air)
head(data_air)
tail(data_air)

good<-complete.cases(data_air)
good

av1data<-data_air[good,][1:6,]

av1data
No_NA_data_air<-data_air[good,]
No_NA_data_air
