# FetchGoogleNews
Fetch Google News RSS in csv format using Python Pandas 0.25


Search through Google News with the "search_term" and get the headlines and the contents of the news that was released today, this week, this month, or this year ("date_filter"). 

```python
get_news(search_term, data_filter)
```

### Parameters
```
search_term  -  a string that will be used by the function to search the news in Google News 
                   e.g. 'Samsung Galaxy Note 9', 'Basketball' 
date_filter  -  date that will filter available news 
                   'today' - get headlines of the news that are released only in today 
                   'this_week' - get headlines of the news that are released in this week 
                   'this month' - news released in this month 
                   'this_year' - news released in this year
                   number - int or str news released in number of days ago
                   or use '' to extract all
                   
```
