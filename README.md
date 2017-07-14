# Fake-REST-API
This is a fake REST API using an incredible tool called JSON-Server. This is used for mocking and prototyping a backend server. It is useful to anyone building frontend apps with something like Angular, React, etc.

# GET ALL USERS
http://localhost:3000/users

# GET SINGLE USER
http://localhost:3000/users/1

# GET ALL COMPANIES
http://localhost:3000/companies

# GET SINGLE COMPANY
http://localhost:3000/companies/1

# GET ALL USERS OF A COMPANY
http://localhost:3000/companies/1/users

# FILTER COMPANIES BY NAME
http://localhost:3000/companies?name=Microsoft
http://localhost:3000/companies?name=Microsoft&name=Apple

# PAGINATION & LIMIT
http://localhost:3000/companies?_page=1&_limit=2

# SORTING
http://localhost:3000/companies?_sort=name&_order=asc

# USERS AGE RANGE
http://localhost:3000/users?age_gte=30
http://localhost:3000/users?age_gte=30&age_lte=40

# FULL TEXT SEARCH
http://localhost:3000/users?q=Paul
