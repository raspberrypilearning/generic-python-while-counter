The purpose of a **while** loop is to repeat code over and over while a condition is `True`. This is why while loops are sometimes referred to as **condition-controlled** loops.

Sometimes while loops are written to repeat a specified number of times:

```python
counter = 0
while counter < 10:
    print("Counting...")
    counter += 1
```
In this example, the condition is `counter < 10`. Since we add `1` to `counter` each time the loop runs, the loop will run 10 times.
