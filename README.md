import string 
from random import *
	 
char = string.ascii_letters + string.punctuation + string.digits
password = "".join(choice(char) for x in range(randint(6,16)))
print("this your password : " , password)

print("by mr.jailbreak")


#run to idle python or terminal linux
