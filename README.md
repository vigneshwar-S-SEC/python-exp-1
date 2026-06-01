# MODULE-1

---

# EXP NO:1 PYTHON PROGRAM TO CONVERT FAHRENHEIT TO CELSIUS

## AIM:
To write a Python program that takes a temperature value in Fahrenheit as input and converts it to Celsius.

## Algorithm:
1. Start.
2. Read the temperature in Fahrenheit from the user and store it in a floating-point variable `f`.
3. Calculate the Celsius equivalent using the formula: `c = (f - 32) / 1.8`
4. Display the original Fahrenheit value formatted to two decimal places.
5. Display the calculated Celsius value formatted to two decimal places.
6. Stop.

## PROGRAM:

```python
f = float(input())
c = (f - 32)/1.8
print(f"Fahrenheit = {f:.2f}")
print(f"Celsius = {c:.2f}")
```

## Output:

<img width="1020" height="401" alt="image" src="https://github.com/user-attachments/assets/f5d8d735-d02c-4849-8c73-66258431c9df" />


## RESULT:
Thus, the Python program to convert temperature from Fahrenheit to Celsius was executed and verified successfully.

---

---

# EXP NO:2 PYTHON PROGRAM TO FIND THE MINIMUM OF THREE NUMBERS

## AIM:
To write a Python program that takes three numbers as input and finds the minimum among them using conditional expressions.

## Algorithm:
1. Start.
2. Read three floating-point numbers from the user and store them in variables `a`, `b`, and `c`.
3. Use a nested conditional expression to determine the smallest value: check if `a` is less than both `b` and `c`. If true, assign `a` to the minimum. Otherwise, check if `b` is less than `c`. If true, assign `b`. Otherwise, assign `c`.
4. Display the original three numbers and the calculated minimum value.
5. Stop.

## PROGRAM:

```python
a=float(input())
b=float(input())
c=float(input())
min = a if (a < b and a < c) else (b if b < c else c)
print(f"The minimum of {a}, {b}, {c} is {min}")
```

## Output:

<img width="1202" height="316" alt="image" src="https://github.com/user-attachments/assets/79971ce9-d361-4242-bc94-e48596e79c47" />


## RESULT:
Thus, the Python program to find the minimum of three numbers was executed and verified successfully.

---

---

# EXP NO:3 PYTHON PROGRAM TO DETERMINE TRAFFIC CONDITIONS

## AIM:
To write a Python program that classifies traffic conditions into high, medium, or low based on a given threshold using if-elif statements.

## Algorithm:
1. Start.
2. Read a numeric value representing the traffic volume from the user and store it in the variable `traffic_volume`.
3. Check if `traffic_volume` is greater than 0.5. If true, print "High Traffic!".
4. If false, check if `traffic_volume` is greater than 0.25 and less than or equal to 0.5. If true, print "Medium Traffic".
5. If false, check if `traffic_volume` is less than 0.25. If true, print "Low Traffic".
6. Stop.

## PROGRAM:

```python
traffic_volume = eval(input())
if (traffic_volume > 0.5):
    print("High Traffic!")
elif(traffic_volume > 0.25 and traffic_volume <= 0.5):
    print("Medium Traffic")
elif (traffic_volume < 0.25):
    print("Low Traffic")
```

## Output:

<img width="555" height="268" alt="image" src="https://github.com/user-attachments/assets/cb94ddeb-5bf7-4ca9-b43a-fe0c1e311b4c" />


## RESULT:
Thus, the Python program to determine traffic conditions based on input thresholds was executed and verified successfully.

---

---

# EXP NO:4 PYTHON PROGRAM TO CALCULATE SIMPLE INTEREST

## AIM:
To write a Python program that takes the principal amount, time period, and rate of interest as input and calculates the simple interest.

## Algorithm:
1. Start.
2. Read the principal amount from the user and store it in the variable `principal`.
3. Read the time period from the user and store it in the variable `time`.
4. Read the rate of interest from the user and store it in the variable `rate`.
5. Calculate the simple interest using the formula: `(principal * rate / 100) * time`
6. Display the calculated simple interest formatted to two decimal places.
7. Stop.

## PROGRAM:

```python
principal = eval(input())
time = eval(input())
rate = eval(input())
print("Simple interest : {:.2f}".format((principal * rate / 100) * time))
```

## Output:

<img width="667" height="315" alt="image" src="https://github.com/user-attachments/assets/0402e364-4a2d-4f79-89ec-f747bbebd964" />


## RESULT:
Thus, the Python program to calculate simple interest was executed and verified successfully.

---

---

# EXP NO:5 PYTHON PROGRAM TO DETERMINE THE TIME OF DAY

## AIM:
To write a Python program that classifies a given 24-hour time integer into specific time of day categories (Morning, Noon, Afternoon, Evening, Night) using conditional statements.

## Algorithm:
1. Start.
2. Read an integer representing the time in 24-hour format from the user and store it in the variable `time`.
3. Check if `time` is between 600 and 1199. If true, print "Morning".
4. If false, check if `time` is exactly 1200. If true, print "Noon".
5. If false, check if `time` is between 1201 and 1700. If true, print "Afternoon".
6. If false, check if `time` is between 1701 and 2000. If true, print "Evening".
7. If false, check if `time` is between 2001 and 2399, or between 0 and 599. If true, print "Night".
8. If none of the above conditions are met, print "Invalid time!".
9. Stop.

## PROGRAM:

```python
time = int(input())
if time >= 600 and time < 1200:
    print("Morning")
elif time == 1200:
    print("Noon")
elif time > 1200 and time <= 1700:
    print("Afternoon")
elif time > 1700 and time <= 2000:
    print("Evening")
elif ((time > 2000) and (time < 2400)) or ((time >= 0) and (time < 600)):
    print("Night")
else:
    print("Invalid time!")
```

## Output:

<img width="502" height="230" alt="image" src="https://github.com/user-attachments/assets/a512ba52-cc57-4fdd-b23f-2a73d2415c53" />


## RESULT:
Thus, the Python program to determine the time of day based on a 24-hour integer format was executed and verified successfully.

---
