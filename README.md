# MidTerm Fall 2022
## Samuel Matthews

- About Me
- My Interests
- Example Project

## About Me
Hello, my name is ***Samuel Matthews.*** I am a student at [Mizzou](https://missouri.edu/) who is taking the Fall 2022 Infotc 1000 class. I am a transfer student from STLCC in St. Louis. I was enrolled in Mizzou earlier in life but when covid 19 struck, I struggled and, in the end, dropped out. I then moved to St. Louis to live with my grandmother and her Great Dane, Gracie. I made sure she was taken care off and safe during the pandemic. While I was there, I also enrolled in STLCC with the end goal of returning to Mizzou. Now I am a **psych major!**   

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR9zeazBxYygXW-T25t_r6xDzJyJcMT4Ps_5lCOuXc&usqp=CAE&s)
## My Interests
I am what you would call a stereotypical nerd. I love dungeons and dragons, magic the gathering, video games and all things fantasy or science fiction. I have a love of classical rock and roll with led zeppelin being my favorite band. I enjoy drawing, whether it be digital or pen and paper, and have dabbled with 3DS Max and Maya in the past. I have a golden doodle named *Freyja* who is the joy of my life. I also have a fascination and love of [Herpetology](https://en.wikipedia.org/wiki/Herpetology). In my life I have owned and cared for many different reptiles including 
- A Brearded Dragon named *Simon*
- A blue tounge skink named *Stacy*
- A corn Snake named *Snake*
- An African Dwarf Frog named *Fred*
- A Leopard Gecko named *Gabby*

Currently I only have one, a Crested Gecko named *Ed*, however I plan to get more very soon.
[Other Animals](https://github.com/SCMatthews0/Pets.git)

![Ed Giving me a BIG hug!](https://user-images.githubusercontent.com/116331873/197120056-0d3b9364-e933-4f59-991a-34f8909b7d68.jpg)
## Example Project
Throughout this course I have worked on many projects in many languages. My favorite was using python to make a calculator. Below is a copy of the code for it. 

```python
#Volume of Cube: length^3 (length * length * length)
#Volume of a Cylinder: pi * r^2 *h (pi * r * r * h)
#volume of a Cone: pi * r * r * (h/3)

def volume_of_a_cube():

    """
    this function finds the volume of a cube
    """
    l = float(input('lenght :'))
    volume = l*l*l
    return volume
    

def volume_of_a_cone():

    """
    this function finds the volume of a cone
    """
    r = float(input('radius :'))
    h = float(input('height :'))
    volume = (3.142*r*r*h)/3
    return volume

def volume_of_a_cylindar():

    """
    this function finds the volume of a cylindar
    """
    r = float(input('radius :'))
    h = float(input('height :'))
    volume= 3.142*r*r*h
    return volume





print("Please pick one of the following")
print("1: Volume of a Cube")
print("2: Volume of a Cone")
print("3: volume of a Cylinder")

user_choice = input("Enter your selection: ")
if(user_choice == "1"):
    volume = volume_of_a_cube()
elif(user_choice == "2"):
    volume = volume_of_a_cone()
elif(user_choice == "3"):
    volume = volume_of_a_cylindar()

print("the volume is:" + str(volume))
```
Other projects I did:
- [TurtleImage](https://github.com/SCMatthews0/Turtle.git)
- [AboutME](https://github.com/SCMatthews0/About-Me.git)
- [VolumeOfACone](https://github.com/SCMatthews0/VolumeCone.git)
