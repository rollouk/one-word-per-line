# one-word-per-line


    # Take a whole book and make it one word per line 
with open('BOOK.txt','r') as f:
    for line in f:
        for word in line.split():
            print(word, file=open("output.txt", "a")) 
            
            
