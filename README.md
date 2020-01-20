# python-microservice
This repository follows - https://medium.com/@ssola/building-microservices-with-python-part-i-5240a8dcc2fb, part 2 and part 3 blog series.


## Part 1 - Commit 1
Very basics

1. Run app.py
   you must get a console message like this -  * Running on http://0.0.0.0:9090/ (Press CTRL+C to quit)
2. Now check swagger ui running at - http://localhost:9090/v1.0/ui/
   Here, you should see a basic swagger ui home screem with only Default endpoint
3. Click on "default"
   you see GET /items/ api (one that is specified in the yaml file)
4. Execute get
   you get results expected results as stated in the blog. (from api/items.py)
