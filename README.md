## Routes 

HTTP GET methods are supported. You can use http or https for your requests.

```bash
# Spesific Joke
GET    : /v1/en/1 until 70

# Filter Joke
GET    : /v1/en?id=1&id=2

# Get Jokes with Limit
GET    : /v1/en?_limit=20

# Get Jokes with Sort
GET    : /v1/en?_sort=id&_order=desc

# Get Jokes with Operator LIKE
GET    : /v1/en?jokes_like=pig

# Get Jokes with Operator Range
GET    : /v1/en?id_gte=1&id_lte=4
```
