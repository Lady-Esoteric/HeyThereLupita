# HeyThereLupita
#My first repository in Github
#I would like for this fruit dictionary to be more functional in Python.
#here is the code. 
fruit = { 'Apple' :'This fruit contains about 81 calories, 21.1 carbs, and has about .1 fat.',
         'Apricot' : 'This fruit contains about 17 calories, 3.9 carbs and has about .1 fat.',
        'Banana' : 'This fruit contains about 105 calories, 26.7 carbs and has about .6 fat.', 
         'Kiwi' : 'This fruit contains about 46 calories, 11.3 carbs, and has about .3 fat.', 
         'Lemon' : 'This fruit contains about 17 calories, 5.4 carbs, and has about 0.2 fat.', 
         'Lime' : 'This fruit contains about 20 calories, 7.1 carbs and no fat at all.', 
         'Mango' : 'This fruit contains about 135 calories, 35.2 carbs, and .6 fat.', 
         'Necturine' : 'This fruit contains about 67 calories, 16 carbs, and .6 fat.', 
         'Orange' : 'This fruit contains about 62 calories, 15.4 carbs, and .2 fat. ', 
         'Papaya' : 'This fruit contains about 117 calories, 29.8 carbs and .4 fat.', 
         'Peach' : 'This fruit contains about 58 calories, 9.7 carbs, and .1 fat.', 
         'Pear' : 'This fruit contains about 98 calories, 25.1 carbs, and .7 fat', 
         'Tangerine' : 'This fruit contains about 37 calories, 9.4 carbs, and .2 fat.'
         }

print(
    """
Welcome to the most delicious dictionary you will ever encounter.
So now if you want to view some of the information about the many
fruits please select from the following in your input"""
)
#this is to inform the user of what this dictionary contains
print("""
Here are the fruits that are listed with nutritional value:

    -Apple
    -Apricot
    -Banana
    -Kiwi
    -Lemon
    -Lime
    -Mango
    -Necturine
    -Orange
    -Papaya
    -Peach
    -Pear
    -Tangerine

FYI: Please do the following input: fruit["insert fruit name here"] 
"""
      )

input = fruit("\n\nType fruit input")
