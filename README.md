# cake-cutting-via-python
from replit import clear
print("WELCOME")
def cake():
 input1 = int(input("How many parts you want to cut the cake in:\n"))
 if 360 % input1 == 0:
 print(f"Yes, the cake can be cut into {input1} different pieces")
 else:
 print(f"No, the cake cannot be cut into {input1} different pieces")
 if input1 < 360:
 print(f"Yes, the cake can cut into {input1} pieces of any size")
 else:
 print(f"No, the cake cannot cut into {input1} pieces of any size")
 if input1 * (input1 + 1) / 2 <= 360:
 print(f"Yes, the cake can cut into {input1} pieces such that no two
of them are equal")
 else:
 print(f"No, the cake can cut into {input1} pieces such that no two of
them are equal")
switch = True
while switch:
 cake()
 again = input("Type 'yes' if you want to run the program again type 'no'
for exit:\n")
 if again == 'no':
 switch = False
 print("Thank you")
