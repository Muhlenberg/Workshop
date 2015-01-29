# Functions and Parameters Worksheet
# SOME COOL CODE
```python
# Example Code 1
# Holly Bertolet 
# 9/16/14

# Draws on a picture starting at a given x and y value
def drawOnPicture(a, b):
  file = pickAFile()
  pic = makePicture(file) 
  drawShape(pic, a, b)
  show(pic)

def drawShape(pic, startX, startY):
  for x in range(startX, startX+30):
    for y in range(startY, startY+30):
      pixel = getPixelAt(pic, x, y)
      setColor(pixel, green)

# Printing example
def brokenPrinter(word):
  for letter in word:
    print(letter + word)
```

Use the above code sample to answer the following questions: 

1. List the functions defined in this program
2. List all the functions that are called by `drawOnPicture`
3. Pick two of these functions and list the parameters they are given
4. Give an example of a function call
5. Out of the four integer variables (`a`, `b`, `startX`, and `startY`), which ones would contain the same exact numerical value?
6. Describe what pic would look like at the end of `drawOnPicture(a, b)`
7. Give an example of how you could run/test `brokenPrinter(word)`
8. What would the output of question 7 be?
