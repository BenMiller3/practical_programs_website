## Welcome to Practical Programs

If you're looking for simple solutions and great software. Look no further.

### Blog

Will begin a technical blog very soon.

The basis for any python program
```python
import sys
import os

def main():
  try:
    arg = sys.argv[1]
  except:
    arg = input("Enter a program argument")
    
  print("You've entered: " + str(arg) + "! :)")

if __name__ == '__main__':
  main()
```

### Support or Contact

Contact me! :)
