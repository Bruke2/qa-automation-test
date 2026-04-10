# Positive Test Case

| Test Case ID | Scenario | Type | Steps | Expected Result |
----------------------------------------------------------------------------------------------------
| TC01 | Get all posts | Positive | Send GET request to /posts | status 200, get all post data |
| TC02 | Get a posts | Positive | Send GET request to /posts/{id = 10} | status 200, get post data that have id = 10|
| TC03 | Post a posts | Positive | Send POST request to /posts | status 200, make a new posts data|

# Negative Test Case

| Test Case ID | Scenario | Type | Steps | Expected Result |
----------------------------------------------------------------------------------------------------
| TC04 | Get all posts | Positive | Send GET request to /posts | status 200, get all post data |
| TC05 | Get a posts | Positive | Send GET request to /posts/{id = 1} | status 200, get post data that have id = 1|
| TC06 | Post a posts | Positive | Send POST request to /posts | status 200, make a new posts data|

# Negative Test Case

| Test Case ID | Scenario | Type | Steps | Expected Result |
----------------------------------------------------------------------------------------------------
| TC07 | Get min id in posts | Positive | Send GET request to /posts/1 | status 200, get post data with id=1 |
| TC08 | Get max id in posts | Positive | Send GET request to /posts/100 | status 200, get post data with id=1|
| TC09 | Post a posts with new field | Positive | Send POST request to /posts with field "file" | status 200|




 