print("""
You are a adventure-loving traveler who travels around the world, searching for mysteries and myths. 
One day, you hear in a news about reported sightings of long-lost temple.
you leave for Brazil to find the temple
You have now landed in the International Airport of Brasilia. 
While you are on the way towards the temple, you are met by The Others. 
The Others are the keeper of the temple. Presumed dead and extinct, they live in hiding and protect the temple and its treasure.
You are warned against entering the temple and taking its treasure
Nevertheless, You find the temple and enter it. 
You find the treasure but suddenly, the Others know about your plan
Your task is to take the treasure and escape the place safely  without getting caught
You need to get out of the temple, find a boat and escape using the river.

You can go four directions: forward, backward, right, left
You have three actions for fighting when applicable: attack,   heal, shield
""")

def actions():
    action = input("""
  Choose an action: 
  forward 
  backward 
  right 
  left 
  action: """)
    if action == "forward":
        print("Wall ahead")
    if action == "backward":
        print("Dead end")
    if action == "right":
        print("Watch out: a snake!")
    if action == "left":
        print(" You are walking to the left side of the temple")
    else:
        print("invalid action")
        actions()


def actions_1():
    action_1 = input("""
  Choose an action: 
  forward 
  backward 
  right 
  left 
  action: """)
    if action_1 == "forward":
        print("Keep walking ahead")
    if action_1 == "backward":
        print("Wrong way!")
    if action_1 == "right":
        print("Wall ahead")
    if action_1 == "left":
        print("Wall ahead")
    else:
        print("Invalid action")
        actions_1()


def actions_2():
    action_2 = input("""
  Choose an action: 
  forward 
  backward 
  right 
  left 
  action: """)
    if action_2 == "forward":
        print("Keep walking ahead")
    if action_2 == "backward":
        print("Wrong way!")
    if action_2 == "right":
        print("Wall ahead")
    if action_2 == "left":
        print("Wall ahead")
    else:
        print("Invalid action")
        actions_2()


def actions_3():
    action_3 = input("""
  Choose an action: 
  forward 
  backward 
  right 
  left 
  action: """)
    if action_3 == "forward":
        print("Dead end")
    if action_3 == "backward":
        print("Wrong way!")
    if action_3 == "right":
        print(" You turn right to keep walking towards the exit")
    if action_3 == "left":
        print("Wrong way! Leads to a room")
    else:
        print("Invalid action")
        actions_3()


actions()
actions_1()
actions_2()
actions_3()
