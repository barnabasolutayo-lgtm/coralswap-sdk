## Provide a simple piece of code (e.g., a Python function with a bug).
  ````  
    def calculate_average(numbers):
    total = 0
    for n in numbers:
        total = total + n
    average = total / len(numbers)
    return average

print(calculate_average([]))
````
## Prompt the model: "Act as a mentor reviewing this code. Provide corrections and explain improvements."
  Corrected Version 
  ```` 
  def calculate_average(numbers):
    if not numbers:
        return None
    return sum(numbers) / len(numbers)
````
- The Bug
 Passing an empty list [] causes a ZeroDivisionError because len([]) returns 0, making the division total / 0 invalid.

- The Fix
 Add a guard clause before the division:
````
pythondef calculate_average(numbers):
if len(numbers) == 0:
        return 0
    total = 0
    for n in numbers:
        total = total + n
    return total / len(numbers)
````

- Three Improvements in Order
  - Use not numbers instead of len(numbers) == 0
   More Pythonic. Empty lists are falsy in Python.
   Replace the loop with sum()
   pythonreturn sum(numbers) / len(numbers)
   Built-in, shorter, less error-prone.
  3. Return None instead of 0 for empty input
   Zero implies a valid result. 
 ## Review the response and check if the role influences feedback style.
   The role instruction did not just change the tone — it changed the purpose of the response.
Without a role the model asks: "what is the correct answer?"
With the mentor role the model asks: "what does this student need to understand?"