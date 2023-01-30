# Third-Assignment

> Name <- c("Jeb", "Donald", "Ted", "Marco", "Carly", "Hillary", "Berine")
> ABC_political_poll_results <- c(4, 62, 51, 21, 2, 14, 15)
> CBS_political_poll_results <- c(12, 75, 43, 19, 1, 21, 19)
> results<-cbind(Name, ABC_political_poll_results, CBS_political_poll_results)
> results
     Name      ABC_political_poll_results CBS_political_poll_results
[1,] "Jeb"     "4"                        "12"                      
[2,] "Donald"  "62"                       "75"                      
[3,] "Ted"     "51"                       "43"                      
[4,] "Marco"   "21"                       "19"                      
[5,] "Carly"   "2"                        "1"                       
[6,] "Hillary" "14"                       "21"                      
[7,] "Berine"  "15"                       "19"                      
> results.df <- data.frame(Name, ABC_political_poll_results, CBS_political_poll_results)
> results.df
     Name ABC_political_poll_results CBS_political_poll_results
1     Jeb                          4                         12
2  Donald                         62                         75
3     Ted                         51                         43
4   Marco                         21                         19
5   Carly                          2                          1
6 Hillary                         14                         21
7  Berine                         15                         19
> colMeans(results.df[,2:3])
ABC_political_poll_results CBS_political_poll_results 
                  24.14286                   27.14286
