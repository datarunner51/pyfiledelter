import os
from os import walk

mypath = ""

print(mypath)

for root, dirs, files in os.walk(mypath, topdown=False):
    for name in files:
        if ".INI" in str(name).upper():
        
            filepath = os.path.join(root, name)
            print(filepath)
            
            # Do stuff here
            #os.remove(filepath)
            
            
print("Complete")
