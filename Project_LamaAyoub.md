# Final Project

## done by Lama Ayoub

## Table of Contents

- [Section 1](#cell-5)
- [Section 2](#cell-10)
- [Section 3](#cell-15)

*Question 1*

# Section 1
# A car with a full tank of gas drives 80 miles per hour for 3 hours before running out of gas. How many miles can the car go per tank?


```python
speed = 80  # miles per hour
time = 3  # hours

distance = speed * time

print("The car can go", distance, "miles per tank.")
```

    The car can go 240 miles per tank.
    

> Question 1 has been completed in python code

- [x] Question 1
- [ ] Question 2
- [ ] Question 3

*Question 2*

# Section 2
# A runner travels a half marathon (13.1 miles) in 3 hours. How fast was this runner going in miles per hour?


```python
distance = 13.1 
time = 3  

speed = distance / time

print("The runner can go at a speed of", speed, "miles per hour.")
```

    The runner can go at a speed of 4.366666666666666 miles per hour.
    

> Question 2 has been completed in python code

- [x] Question 1
- [x] Question 2
- [ ] Question 3

*Question 3*

# Section 3
# The spread of a virus is exponential. If 5 people are infected and each person infects 2 other people, how many people have been infected after 5 rounds of infection?


```python
infected = 5
rounds = 5

for _ in range(rounds):
    infected *= 2

print("The number of infected people after 5 rounds is:", infected)
```

    The number of infected people after 5 rounds is: 160
    

> Question 3 has been completed in python code

- [x] Question 1
- [x] Question 2
- [x] Question 3


```python
from IPython.display import Image

image_path = r"C:\Users\user\Pictures\project_image.jpg"

Image(filename=image_path)

```




    
![jpeg](output_18_0.jpg)
    




```python

```
