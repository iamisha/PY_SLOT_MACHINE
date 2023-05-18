## PY_SLOT_MACHINE



#### For collecting user input that gets the deposit from the user.
```python
def deposit():
```

#### Inside `while loop` I'm gonna continuously ask the user to enter deposit amount until they give me a vlid amount.
```python
while True:

```
#### So if they don't give me a valid amount, then they need  to keep typing in until eventually we get one.

#### To check the amount actually is a number before i get out of this wallet.
```python
if amount.isdigit():
```

#### To convert the string value into the integer value
```python
amount = int(amount)
```

#### If amount > 0, the loop should break out of the while loop as
```python
if amount > 0:
    break
```