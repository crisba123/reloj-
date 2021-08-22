v= 0

def setup() :
    size(300, 600)

def draw() :
    global v 
    background(175)


    ellipse(width/ 2, v, 50, 50)
    fill(232, 5, 24)
    if ? > height :
        v = 0
    else:
        v = map(second(), 0, 59, 0, height)




    ellipse(width/ 2, v, 50, 50)
    fill(245, 25, 25)
    if ? > height :
        v = 0
    else:
        v = map(minute(), 0, 60, 0, height)





    ellipse(width/ 2, v, 50, 50)
    fill(75, 25, 245)
    if ? > height :
        v = 0
    else:
        v = map(hour(), 0, 24, 0, height)
