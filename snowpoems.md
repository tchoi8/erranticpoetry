

    poem="absence absenteeism cut nonappearance trauncy AWOL hooky nonattendance vacancy no-show".split()
    import random
    
    while len(poem)>0:
      poem.remove(random.choice(list(poem)))
      print ' '.join(poem)

    absence absenteeism cut nonappearance trauncy hooky nonattendance vacancy no-show
    absence absenteeism nonappearance trauncy hooky nonattendance vacancy no-show
    absence absenteeism nonappearance trauncy hooky nonattendance no-show
    absence absenteeism trauncy hooky nonattendance no-show
    absence trauncy hooky nonattendance no-show
    absence trauncy hooky no-show
    absence hooky no-show
    absence no-show
    no-show
    



    poem = ' A poem that fall like snow in a March morning.'
    replace = {'A':'<', 'a':'^','e':'{','i':'%', 'y':'$', 'o':'@', 'u':'&'}
    txt = replace_all(poem, replace) 
    print txt 

     < p@{m th^t f^ll l%k{ sn@w %n ^ M^rch m@rn%ng.



    s="< p@{m th^t f^ll l%k{ sn@w %n ^ M^rch m@rn%ng.".split()
    import random
    
    while len(s)>0:
      s.remove(random.choice(list(s)))
      print ' '.join(s)

    < p@{m th^t f^ll l%k{ sn@w %n ^ m@rn%ng.
    < p@{m th^t f^ll sn@w %n ^ m@rn%ng.
    < p@{m f^ll sn@w %n ^ m@rn%ng.
    < p@{m sn@w %n ^ m@rn%ng.
    p@{m sn@w %n ^ m@rn%ng.
    p@{m sn@w %n m@rn%ng.
    p@{m sn@w %n
    p@{m sn@w
    p@{m
    

