

    from random import choice, randint
    
    adjectives = "Absence Cut Vacancy Holiday Hooky".split()
    verbs = "presence existence company being habitation ".split()
    nouns = "distance area gap orbit expansion".split()
    
    def errantic_poem():
        
        for x in range(randint(40,55)):
            words1 = " ".join([choice(adjectives)])
            words2 = " ".join([choice(verbs)])
            words3 = " ".join([choice(nouns)])
            
            for i in range(randint(1,1)):
                words = choice([words1])
                nords = choice([words2])
                mords = choice([words3])
                
                
                print (words + "\t" + "is" + "\t"  +  words2 + "\t" + "with" + " "*3 + mords + ".").expandtabs(16)
                 
                 
    errantic_poem()
    
    text_file = open('output.txt', 'w')
    text_file.write('my string i want to put in file')
    text_file.close()

    Holiday         is              habitation      with   orbit.
    Cut             is              existence       with   orbit.
    Absence         is              company         with   distance.
    Vacancy         is              existence       with   area.
    Cut             is              habitation      with   area.
    Holiday         is              existence       with   orbit.
    Cut             is              existence       with   orbit.
    Vacancy         is              company         with   distance.
    Absence         is              presence        with   expansion.
    Holiday         is              habitation      with   orbit.
    Cut             is              company         with   orbit.
    Hooky           is              presence        with   expansion.
    Vacancy         is              presence        with   orbit.
    Hooky           is              company         with   orbit.
    Holiday         is              company         with   distance.
    Holiday         is              presence        with   distance.
    Cut             is              existence       with   expansion.
    Absence         is              existence       with   orbit.
    Vacancy         is              being           with   expansion.
    Cut             is              presence        with   expansion.
    Hooky           is              existence       with   gap.
    Cut             is              habitation      with   orbit.
    Holiday         is              habitation      with   area.
    Vacancy         is              existence       with   distance.
    Absence         is              existence       with   gap.
    Holiday         is              existence       with   orbit.
    Absence         is              presence        with   orbit.
    Vacancy         is              being           with   expansion.
    Holiday         is              existence       with   area.
    Hooky           is              being           with   gap.
    Vacancy         is              existence       with   area.
    Holiday         is              presence        with   orbit.
    Cut             is              habitation      with   area.
    Hooky           is              presence        with   orbit.
    Vacancy         is              habitation      with   expansion.
    Holiday         is              company         with   area.
    Absence         is              company         with   gap.
    Absence         is              being           with   distance.
    Absence         is              presence        with   gap.
    Hooky           is              existence       with   orbit.
    Holiday         is              presence        with   gap.
    Vacancy         is              being           with   gap.
    Holiday         is              existence       with   expansion.
    Holiday         is              presence        with   distance.
    Holiday         is              being           with   gap.
    Absence         is              presence        with   expansion.
    Cut             is              being           with   expansion.
    Cut             is              presence        with   distance.
    Absence         is              presence        with   area.
    Vacancy         is              existence       with   area.
    Absence         is              presence        with   gap.
    Cut             is              habitation      with   gap.
    Holiday         is              habitation      with   distance.
    Absence         is              being           with   orbit.
    Cut             is              presence        with   area.



    
