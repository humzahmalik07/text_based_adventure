# Course: CS 30
# Period: 2
# Date created: 19/07/21
# Date last modified: 21/07/21
# Name: Humzah Zahid Malik
# Description: Escape from the temple

# prints the introduction of the game
print("""
You are a adventure-loving traveler who travels around the world.
searching for mysteries and myths.
One day, you hear in a news about reported sightings of long-lost temple.
you leave for Brazil to find the temple
You have now landed in the International Airport of Brasilia.
While you are on the way towards the temple, you are met by The Others.
The Others are the keeper of the temple. Presumed dead and extinct.
They live in hiding and protect the temple and its treasure.
You are warned against entering the temple and taking its treasure.
Nevertheless, You find the temple and enter it.
You find the treasure but suddenly, the Others know about your plan.
Your task is to take the treasure and escape the place without getting caught.
You need to get out of the temple, find a boat and escape using the river.
You are in a maze. You need to find your way out of the temple.

You can go four directions: forward, backward, right, left
""")


# valid directions and actions for the characters
valid_actions = ["forward", "backward", "left", "right"]
# print a list a valid actions before user input.

# This defines the menu for the actions


def menu():
        print("""Choose an action:
    """)
        for action in valid_actions:
            print(f"* {action}")

# This defines the first action of the game


def action_1():
        print("""
      LEVEL 1
      """)
        menu()
        action_input = input("Action: ")
        if action_input.lower() in valid_actions[0]:
            print(f" Wall ahead ")
            action_1()
        if action_input.lower() in valid_actions[1]:
            print(f" Wrong way! ")
            action_1()
        if action_input.lower() in valid_actions[2]:
            print(f" You are turning to the left side of the temple")
            action_2()
        if action_input.lower() in valid_actions[3]:
            print(f" Wall ahead ")
            action_1()
        elif action_input.lower not in valid_actions:
            print("Invalid direction!")
            action_1()

# This defines the second action by the user


def action_2():
        print("""
        LEVEL 2
        """)
        menu()
        action_input = input("Action: ")
        if action_input.lower() in valid_actions[0]:
            print(f" Keep walking ahead ")
            action_3()
        if action_input.lower() in valid_actions[1]:
            print(f" Wrong way! ")
            action_2()
        if action_input.lower() in valid_actions[2]:
            print(f" Wall ahead")
            action_2()
        if action_input.lower() in valid_actions[3]:
            print(f" Wall ahead ")
            action_2()
        elif action_input.lower not in valid_actions:
            print("Invalid direction!")
            action_2()

# This defines the third action by the user


def action_3():
        print("""
        LEVEL 3
        """)
        menu()
        action_input = input("Action: ")
        if action_input.lower() in valid_actions[0]:
            print(f" Keep walking ahead")
            action_4()
        if action_input.lower() in valid_actions[1]:
            print(f" Wrong way! ")
            action_3()
        if action_input.lower() in valid_actions[2]:
            print(f" Wall ahead")
            action_3()
        if action_input.lower() in valid_actions[3]:
            print(f" Wall ahead ")
            action_3()
        elif action_input.lower not in valid_actions:
            print("Invalid direction!")
            action_3()

# This defines the fourth action by the user


def action_4():
        print("""
        LEVEL 4
        """)
        menu()
        action_input = input("Action: ")
        if action_input.lower() in valid_actions[0]:
            print(f" Dead end ")
            action_4()
        if action_input.lower() in valid_actions[1]:
            print(f" Wrong way! ")
            action_4()
        if action_input.lower() in valid_actions[2]:
            print(f" Wall ahead")
            action_4()
        if action_input.lower() in valid_actions[3]:
            print(f" Turn right to walk towards the exit ")
            action_5()
        elif action_input.lower not in valid_actions:
            print("Invalid direction!")
            action_4()

# This defines the fifth action by the user


def action_5():
        print("""
        LEVEL 5
        """)
        menu()
        action_input = input("Action: ")
        if action_input.lower() in valid_actions[0]:
            print(f" Keep walking")
            action_6()
        if action_input.lower() in valid_actions[1]:
            print(f" Wrong way! ")
            action_5()
        if action_input.lower() in valid_actions[2]:
            print(f" Wall ahead")
            action_5()
        if action_input.lower() in valid_actions[3]:
            print(f" Wall ahead ")
            action_5()
        elif action_input.lower not in valid_actions:
            print("Invalid direction!")
            action_5()

# This defines the sixth action by the user


def action_6():
        print("""
        LEVEL 6
        """)
        menu()
        action_input = input("Action: ")
        if action_input.lower() in valid_actions[0]:
            print(f" Keep walking")
            action_7()
        if action_input.lower() in valid_actions[1]:
            print(f" Wrong way! ")
            action_6()
        if action_input.lower() in valid_actions[2]:
            print(f" Wall ahead")
            action_6()
        if action_input.lower() in valid_actions[3]:
            print(f" Wall ahead ")
            action_6()
        elif action_input.lower not in valid_actions:
            print("Invalid direction!")
            action_6()

# This defines the seventh action by the user


def action_7():
        print("""
        LEVEL 7
        """)
        menu()
        action_input = input("Action: ")
        if action_input.lower() in valid_actions[0]:
            print(f" wall ahead ")
            action_7()
        if action_input.lower() in valid_actions[1]:
            print(f" Wrong way! ")
            action_7()
        if action_input.lower() in valid_actions[2]:
            print(f" Wall ahead")
            action_7()
        if action_input.lower() in valid_actions[3]:
            print(f" turn right towards the exit ")
            action_8()
        elif action_input.lower not in valid_actions:
            print("Invalid direction!")
            action_7()

# This defines the eighth action by the user


def action_8():
        print("""
        LEVEL 8
        """)
        menu()
        action_input = input("Action: ")
        if action_input.lower() in valid_actions[0]:
            print(f" wall ahead ")
            action_8()
        if action_input.lower() in valid_actions[1]:
            print(f" Wrong way! ")
            action_8()
        if action_input.lower() in valid_actions[2]:
            print(f" Turn left. You are getting closer!")
            action_9()
        if action_input.lower() in valid_actions[3]:
            print(f" Wall ahead ")
            action_8()
        elif action_input.lower not in valid_actions:
            print("Invalid direction!")
            action_8()

# This defines the ninth action by the user


def action_9():
        print("""
        LEVEL 9
        """)
        menu()
        action_input = input("Action: ")
        if action_input.lower() in valid_actions[0]:
            print(f""" You found the exit! """)
            end_script()
            quit()
        if action_input.lower() in valid_actions[1]:
            print(f" Wrong way! ")
            action_9()
        if action_input.lower() in valid_actions[2]:
            print(f" Wall ahead")
            action_9()
        if action_input.lower() in valid_actions[3]:
            print(f" Wall ahead ")
            action_9()
        elif action_input.lower not in valid_actions:
            print("Invalid direction!")
            action_9()

# This function prints out the ending message of the game


def end_script():
    print("""
    You have successfully escaped out of the temple and
    you have completed the game.
    """)

while True:
    action_1()
    action_2()
    action_3()
    action_4()
    action_5()
    action_6()
    action_7()
    action_8()
    action_9()
