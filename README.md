<h1>👋 Hi, I'm @Lone1y-Mw </h1>

```python
from GitHub import ReadMe
import random, sys, os

os.system("clear") if sys.platform == "linux" else os.system("cls")

ReadMe.init()

def README():
    username = "binu__"
    age = "~"
    location = "South Korea"
    infos = {
        "Instagram profile": "@7azioxp"
    }
    print("Hi my name is " + username + " and I am " + age + " years old")
    print("I live in " + location)
    print("You can contact me here: " + random.choice(infos))
    input("Press enter when you're done reading")
    
if __name__ == "__main__":
    os.system("title About me & mode con: cols=90 lines=30")
    README()
```
    
```python
    Output: 
Hi my name is binu__ and I am 16 years old
I live in South Korea
You can contact me here: @7azioxp
Press enter when you're done reading
```
