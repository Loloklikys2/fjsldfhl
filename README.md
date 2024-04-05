# fjsldfhl
x1 = 0
x2 = 1
def setup():
    size(1200,1000)
    
def draw():
    background(149,255,233)
    global x1
    global x2
    ellipse(500,x1,50,50)
    x1 = x1 + x2
    if x1 >1000:
        x2=-1
