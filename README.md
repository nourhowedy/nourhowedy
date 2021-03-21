with open("datasets.txt") as openfile:
    word= "airship"
    for line in openfile:
        for part in line.split():
            if "boat" in part:
                print (line)
            if "ship" in part:
                 print (line)
                 if word in part:
                     continue
              
            
                 
                 
