# You are a adventure-loving traveler who travels around the world, searching for mysteries and myths. 
# One day, you hear in a news about reported sightings of long-lost temple.
# you leave for Brazil to find the temple
# You have now landed in the International Airport of Brasilia. 
# While you are on the way towards the temple, you are met by The Others. 
# THe Others are the keeper of the temple. Presumed dead and extinct, they live in hiding and protect the temple and its treasure.
# You are warned against entering the temple and taking its treasure
# Nevertheless, You find the temple and enter it. You find the treasure but suddenly, the Others know about your plan
# Your task is to take the treasure and escape the place safely without getting caught
# You need to get out of the temple, find a boat and escape using the river.
# You can go four directions: forward, backward, right, left
# You have four actions: attack, heal, inventory, shield

def actions_list():
  print("forward")
  print("backward")


def actions():
  action = input("Choose an action: forward, backward, right, left: ")
  if action == "forward":
      print("Wall ahead")
  if action == "backward":
      print("Dead end")
  if action == "right":
      print("Watch out: a snake!")
  if action == "left":
      print(" You are walking to the left side of the temple")

actions()
