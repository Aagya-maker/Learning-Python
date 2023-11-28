# Learning-Python (If i was learning Python, I would be better at it, else, I wouldn't..obviously)
# Python is super easy until it begins to feel a little difficult. But that's life, I guess. Anyway, this is some beginner stuff so let me begin with if, else and elif statement. Pay attention to the syntaxes as you should. Let's say that you are living in a country where you are allowed to drink after 18. Let's say that you would want the user to enter their age. If they are over 18, you would say "You are allowed to drink.". If they are under 18, you would say, "You are not allowed to drink." BUT, if they are exactly 18, you would want to say "Piss off!", just for the fun of it. How would you write it in Python? It's simple.
age=int(input("Enter your age"))
if age>18:
   print("You are allowed to drink.")
elif age==18:
   print("Piss off!")
else:
   print("You are allowed to drink.")
