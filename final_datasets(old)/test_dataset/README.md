## Test dataset generate from the Netflix dataset

This dataset is a subset of the original dataset. It contains 1k random less active 
users (smaller count of ratings) and their respective ratings list. The total amount
of rated movies within this subset is **62,749**. The number of movies rated per user
varies from **7 up to 157**.

- ./random_1k_less_active_users_moviesList

The folder './random_1k_less_active_users_moviesList' contains 1000 text files
named 'xxx_movies.txt', where 'xxx' is the id of a user. The sctructure of each file
is 'movied_id, rate'.

For instance, if the file '1001143_movies.txt' contains:
```
289, 5
429, 5
483, 4
550, 5
...
```

we know that the user  with id 1001143 has given rate 5 for the movie with id 289, and so on.

- random_1k_less_active_users.txt

Text file contaning the list of user ids and their respective ratings count. The sctructure 
of each file is 'movied_id, rate'.
```
305344, 7
387418, 50
2439493, 35
1664010, 81
2118461, 157
...
```
we know that the user  with id 305344 have rated 7 movies, and so on.



