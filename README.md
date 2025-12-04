def turn_right():
    for i in range(3):
        r.turn_left()

def one():
    r.move(9)
    r.turn_left()
    r.move(1)
    r.turn_left()
    r.move(9)
    turn_right()
    r.move(1)
    turn_right()

for i in range(5):
    one()
