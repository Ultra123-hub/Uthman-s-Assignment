# R Language For Creating Data Table
A class lab exercise given by Mr. Tochuwkwu from University of Ibadan, Laboratory for Interdisciplinary Statistical Analysis


#### Replicate list of movies, artists and release years in list, dataframe and array


Using list

```r
l=list('name_of_movies'=c('The Banker','Those who wish me dead','Rampage','Hobs and Shaw','Bad Boys for Life','Wrath of Man','Jungle Cruise','Iron Monkey','Drunken Master','Snake in the Eagle shadow','Acrimony','Not a Time to Die','Lion King','Citation','King of Boys'),'Artist'=c('Samuel L Jackson','Angelina Jolie','Dwayne Johnson','Dwayne Johnson','Will Smith','Jason Statham','Dwayne Johnson','Jet Li','Jackie Chan','Jackie Chan','Lady-Lady','James Bond','Beyonce','Temi Otedola','Adesua Etomi'),'Release Year'=c(2020,2020,2020,2019,2019,2021,2021,1989,1989,1989,2018,2021,2019,2020,2019))
```


Using dataframe

```r
d=data.frame('name_of_movies'=c('The Banker','Those who wish me dead','Rampage','Hobs and Shaw','Bad Boys for Life','Wrath of Man','Jungle Cruise','Iron Monkey','Drunken Master','Snake in the Eagle shadow','Acrimony','Not a Time to Die','Lion King','Citation','King of Boys'),'Artist'=c('Samuel L Jackson','Angelina Jolie','Dwayne Johnson','Dwayne Johnson','Will Smith','Jason Statham','Dwayne Johnson','Jet Li','Jackie Chan','Jackie Chan','Lady-Lady','James Bond','Beyonce','Temi Otedola','Adesua Etomi'),'Release Year'=c(2020,2020,2020,2019,2019,2021,2021,1989,1989,1989,2018,2021,2019,2020,2019))
```


Using array

```r
a=array(c('name_of_movies','The Banker','Those who wish me dead','Rampage','Hobs and Shaw','Bad Boys for Life','Wrath of Man','Jungle Cruise','Iron Monkey','Drunken Master','Snake in the Eagle shadow','Acrimony','Not a Time to Die','Lion King','Citation','King of Boys','Artist','Samuel L Jackson','Angelina Jolie','Dwayne Johnson','Dwayne Johnson','Will Smith','Jason Statham','Dwayne Johnson','Jet Li','Jackie Chan','Jackie Chan','Lady-Lady','James Bond','Beyonce','Temi Otedola','Adesua Etomi','Release Year',2020,2020,2020,2019,2019,2021,2021,1989,1989,1989,2018,2021,2019,2020,2019),c(16,3))
```
