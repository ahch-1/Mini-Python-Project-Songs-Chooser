# Mini-Python-Project-Songs-Chooser
import random

sadness = ["You should see me in a crown", "harleys in hawaii", "happiest girl"]
joy = ["Bboom Bboom", "Last friday night", "Cheer up"]
boredom = ["Icy", "Monster", "Fate of ophelia"]
energized = ["Crazy over you", "OMG", "Girls will be girls"]
mad = ["34+35", "You drive me crazy", "Alone"]
emotions = [sadness, joy, boredom, energized, mad]
def choosing_song():
    global emotions
    while True :
        player = input("how are you feeling today?    ")
    
        if player == "sad" :
            print(random.choice(sadness))
        elif player == "happy" :
            print(random.choice(joy))
        elif player == "bored" :
            print(random.choice(boredom))
        elif player == "energetic" :
            print(random.choice(energized))
        elif player == "angry" :
            print(random.choice(mad))
        else  :
            print("wait till next update!")
       
        
choosing_song()
