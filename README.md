# javaproject
Library Management System

#Clone from git: https://github.com/AlmiraAlasani/JavaProject

#How to run This Project

1.Import database from library.sql

2.Open Project

3.Go to src/main/com.example.demo/demoApplication.java

4.Run Demo Application

#Endpoint

#Costumer endpoint

1.URL: http://localhost:8080/costumer Get all Costumer - METHOD = GET

Response: [{ "id": 1,"name": "Meriton","surname": "Ademi"}, {"id": 4,"name": "Almira","surname": "Alasani" }, {"id": 5,"name": "Ali ","surname": "Amzai"}]

2.URL: http://localhost:8080/costumer/ Get Costumer by id - METHOD = GET

Response: {"id": 4,"name": "Almira","surname": "Alasani" }

3.URL: http://localhost:8080/costumer/ Edit Costumer by id - METHOD = PUT

Response: { "id": 4, "name": "Almira", "surname": "Alasani" }

4.URL: http://localhost:8080/costumer/ Add Costumer- METHOD = POST

Response: { "id": 5, "name": "Almira", "surname": "Alasani" }

5.URL: http://localhost:8080/costumer/ Delete Costumer by id- METHOD = DELETE

#Book Endpoint

1.URL: http://localhost:8080/book Get all Book - METHOD = GET

Response: {"id": 11, "name": "Test", "author": "Meriton Ademi", "description": "ss"}

2.URL: http://localhost:8080/book/ Get Book by id - METHOD = GET

Response: {"id": 11, "name": "Test", "author": "Meriton Ademi", "description": "ss"}

3.URL: http://localhost:8080/book/ Edit Book by id - METHOD = PUT

Response: { "id": 11, "name": "Test", "author": "Meriton Ademi", "description": "ss" }

4.URL: http://localhost:8080/book/ Add Book- METHOD = POST

Response: { "id": 12, "name": "Test", "author": "Meriton Ademi", "description": "ss" }

5.URL: http://localhost:8080/book/ Delete Book by id- METHOD = DELETE

#Booking endpoint

1.URL: http://localhost:8080/booking Get all Booking - METHOD = GET

Response: [{"id": 2,"bookid": {"id": 2,"name": "Test","author": "Meriton Ademi","description": "ss"},"costumerid": {"id": 1,"name": "Meriton","surname": "Ademi"},"loaned": "2022-01-10","returned": "2022-01-27"},{ "id": 7,"bookid": { "id": 11,"name": "Test","author": "Meriton Ademi","description": "ss"},"costumerid": {"id": 5,"name": "Ali ","surname": "Amzai"},"loaned": "2022-02-10","returned": "2022-02-25"}]

2.URL: http://localhost:8080/booking/ Get Booking by id - METHOD = GET

Response: { "id": 7,"bookid": { "id": 11,"name": "Test","author": "Meriton Ademi","description": "ss"},"costumerid": {"id": 5,"name": "Ali ","surname": "Amzai"},"loaned": "2022-02-10","returned": "2022-02-25"}

3.URL: http://localhost:8080/booking/ Edit Booking by id - METHOD = PUT

Response: {"id": 7,"bookid": { "id": 11,"name": "Test","author": "Meriton Ademi","description": "ss"},"costumerid": {"id": 5,"name": "Ali ","surname": "Amzai"},"loaned": "2022-02-10","returned": "2022-02-25"}

4.URL: http://localhost:8080/booking/ Add Booking- METHOD = POST

Response: { "id":8 "bookid": { "id": 2, "name": "Test", "author": "Meriton Ademi", "description": "ss" }, "costumerid": { "id": 1, "name": "Meriton", "surname": "Ademi" }, "loaned": "2022-11-10", "returned": "2022-01-27" }

5.URL: http://localhost:8080/booking/ Delete Booking by id- METHOD = DELETE
