# Assignment_3
## Query 1:
### db.movies.find({"year":1983,"runtime":{$gt:200}},{"title":1,"year":1,"runtime":1,"_id":0})
![Screenshot 2025-04-01 125228](https://github.com/user-attachments/assets/bd117f06-cab1-4d46-8bf6-4ecf2391521c)
## Query 2: 
### db.movies.find({"year":{$gt:2014},"imdb.rating":{$gt:9}},{"title":1,"year":1,"imdb.rating":1,"_id":0});
![image](https://github.com/user-attachments/assets/d655f653-ea80-4e7d-a90a-0ee21fb5cfab)
