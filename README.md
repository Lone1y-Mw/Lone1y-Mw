<h1>👋 Hi, I'm @Lone1y-Mw </h1>

- 🚀  Middle School Student
- 🌱  Studying Overall Thing about Programming
- ⛏️  Deciding What I want to do

```
from GitHub import ReadMe
import random, sys, os

os.system("clear") if sys.platform == "linux" else os.system("cls")

ReadMe.init()

def README():
    username = "yubin"
    age = "16"
    location = "South Korea"
    programming_language = "Python"
    infos = {
        "Facebook profile": "https://www.facebook.com/profile.php?id=100046960400174",
        "Instagram profile": "@x_1.mv"
    }
    contacts = [
        "@x_1.mv",
        "@x.1uqdxque",
        "#5900"
    ]
    print("Hi my name is " + username + " and I am " + age + " years old")
    print("I live in " + location)
    print("Self learner of " + programming_language)
    print("You can contact me here: " + random.choice(contacts))
    input("Press enter when you're done reading")
    
if __name__ == "__main__":
    os.system("title About me & mode con: cols=90 lines=30")
    README()
```
    
```
    Output: 
Hi my name is yubin and I am 16 years old
I live in South Korea
Self learner of Python
You can contact me here: @x_1.mv
Press enter when you're done reading
```
