import time
import os

def print_heart():
    heart = [
        "  ***     ***  ",
        " *****   ***** ",
        "******* *******",
        " ************* ",
        "  ***********  ",
        "   *******     ",
        "    *****      ",
        "     ***       ",
        "      *        "
    ]
    
    message = "Eu te amo, minha princesa\nAss: Seu grande amor, Rodrigo"
    
    for _ in range(10):
        os.system('cls' if os.name == 'nt' else 'clear')
        for line in heart:
            print(line.replace('*', '❤'))  # Substitui * por ❤ para mais romantismo
        print("\n" + message)
        time.sleep(0.5)
        
        os.system('cls' if os.name == 'nt' else 'clear')
        for line in heart:
            print(" " + line.replace('*', '❤'))
        print("\n" + message)
        time.sleep(0.5)

if __name__ == "__main__":
    print_heart()

