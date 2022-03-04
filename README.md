#Crate a Mini Project of All artimatics oprations with help of Menu driven
#project1.py
import sys
from oprations import sumop,subop,mulop,divop,modop,expo
from aopmenu import menu
while(True):
	menu()
	ch=int(input("Enter The your choice: "))
	match(ch):
		case 1:
			sumop()
		case 2:
			subop()
		case 3:
			mulop()
		case 4:
			divop()
		case 5:
			modop()
		case 6:
			expo()

		case 7:
			print("\tThank you so much for review/checking my This Program")
			sys.exit()
		case _:
			print("\tWrong Input-----Please try again")
