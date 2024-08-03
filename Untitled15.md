# BMI CALCULATOR


```python
'''
# BMI calculator

In this project, we are going to write a python program to calculate the BMI.

Measurements:
Weight(Kgs)
Height(m)

BMI = Weight/(Height * Height)

We will use the BMI to determine whether the user is Overweight, Normal, or underweight.
'''
```


```python
name = input('What is your name: ').capitalize()
weight = float(input('What is your body weight in Kilograms:'))
height = float(input(' What is your height in Metres:'))
BMI = weight/(height*height)
# BMI categorization
if BMI > 25:
    print(f'{name} Your BMI is: {BMI} rated overweight')
elif 18 < BMI < 25:
    print(f' {name} Your BMI is: {BMI} rated Normal Weight')
else:
    print(f' {name} Your BMI is: {BMI} rated Under Weight')
```


```python

```
