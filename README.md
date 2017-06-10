# Check-Please-
# Tax and tip function

def tip_tax():

    meal = (250)
    
    tax = meal * .0875
    tip = meal * .18
    
    
    total = meal + tax + tip
    print("Total is ${}".format(total))
    
tip_tax()
