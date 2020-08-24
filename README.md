# password-generator

import string
import random
if __name__ == '__main__':

    s1 = string.ascii_uppercase
    #print(s1)

    s2 = string.ascii_lowercase
   # print(s2)

    s3 = string.digits
   # print(s3)

    s4 = string.punctuation
    #print(s4)


    a = int(input('ENTER A PASSWORD LENGTH/n'))

    s = []
    s.extend(list(s1))
    s.extend(list(s2))
    s.extend(list(s3))
    s.extend(list(s4))

    #sprint(s)

    random.shuffle(s)
    #print(s)

    print("YOUR PASSWORD IS: ")

    print("".join(s[0:a]))






