
# Object Data Types
## Practice Worksheet


### Ruby Operations on Basic Object Types

Without putting the code into Ruby or IRB predict the output and data-type of the following?

1.  Value _______32___   Data Type: _integer________  

    ```ruby
    num = 27
    num = num + 5
    num
    ```

1.  Value ___6_______   Data Type: ____integer_____  


    ```ruby
    num = 2
    num = num + num + 2
    num
    ```
1.  Value ____"44"______   Data Type: ____string_____  


    ```ruby
    num = "4"
    num = num + num
    num
    ```

1.  Value ____"dinosaur astronaut"______   Data Type: ___string______  

    ```ruby
    cool_thing = "dinosaur"
    awesome_thing = "astronaut"
    rad_thing = cool_thing + " " + awesome_thing
    rad_thing
    ```

1.  Value ________16__   Data Type: ___integer______  

    ```ruby
    num = 2
    num = num * num
    num = num * num
    num
    ```

1.  Value ______0____   Data Type: ___integer______  

    ```ruby
    num = 27
    answer = num % 3
    answer
    ```

1.  Value ____12______   Data Type: _____integer____  

    ```ruby
    num = 100
    num = num / 2
    num = num / 2
    num = num / 2
    num
    ```

1.  Value ___12.5_______   Data Type: _float________  

    ```ruby
    num = 100.0
    num = num / 2
    num = num / 2
    num = num / 2
    num
    ```

1.  Value _____2.0	_____   Data Type: _float________  

    ```ruby
    num = 5.0
    num = num * 2 + 3
    num = num / 2
    ```

1.  Value ______:dan____   Data Type: ___symbol______  

    ```ruby
    answer = :dan
    answer
    ```

1.  Value _____["Pikachu", "Bulbasaur", "Squirtle", "Charizard"]_____   Data Type: ___array______  

    ```rubylist = ["Pikachu", "Bulbasaur", "Squirtle", "Charizard"]
    list
    
    ```

1.  Value __"Charizard"________   Data Type: __string______  

    ```ruby
    list = ["Pikachu", "Bulbasaur", "Squirtle", "Charizard"]
    list[3]
    ```

1.  Value ___"Bulbasaur"_______   Data Type: ___string______  

    ```ruby
    list = ["Pikachu", "Bulbasaur", "Squirtle", "Charizard"]
    list[1]
    ```

1.  Value _______3___   Data Type: ____integer_____  

    ```ruby
    list = ["Pikachu", "Bulbasaur", "Squirtle", "Charizard"]
    list.length
    ```

1.  Value ___"pikachu"_______   Data Type: _string________  

    ```ruby
    list = ["Pikachu", "Bulbasaur", "Squirtle", "Charizard"]
    list.first
    ```

1.  Value __nil________   Data Type: __nilclass_______  

    ```ruby
    list = ["Pikachu", "Bulbasaur", "Squirtle", "Charizard"]
    list[4]
    ```

1.  Value ___"charizard"______   Data Type: ___string_____  

    ```ruby
    list = ["Pikachu", "Bulbasaur", "Squirtle", "Charizard"]
    list[-1]
    ```

1.  Value ____{:name=> "Pikachu",:type=>:electric,:species=> "Mouse Pokemon",:height=> 0.41,:weight=> 6.0,:id=>25 }_____DataType: ___Hash______  

    ```rubypikachu = {
	  name: "Pikachu",
	  type: :electric,
	  species: "Mouse Pokemon",
	  height: 0.41,
	  weight: 6.0,
	  id: 25
    }
    pikachu
    
    ```

1.  Value ____"pikachu"______   Data Type: ___string______  

    ```ruby
    pikachu = {
	  name: "Pikachu",
	  type: :electric,
	  species: "Mouse Pokemon",
	  height: 0.41,
	  weight: 6.0,
	  id: 25
    }
    pikachu[:name]
    ```

1.  Value ____25______   Data Type: ____integer_____  

    ```ruby
    pikachu = {
      name: "Pikachu",
      type: :electric,
      species: "Mouse Pokemon",
      height: 0.41,
      weight: 6.0,
      id: 25
    }
    pikachu[:id]
    ```


### Comprehension Questions

1. Given a variable `list` which is an array:list=[]
    * How would you print the last element of the array?   list[-1]
    * How about the first? list[0]
1. Compare and contrast arrays and hashes. How are they similar, and how do they differ?
              Arrays                                                           Hashes

Arrays are ordered lists of items                                   Hashes are a collection of paired information

similarities:
Arrays  are collections that store and retrieve data                Hashes are collections that store and retrieve data 
Differences:
Arrays store values, but have fixed indexes                         Hashes store data but define the index as any object
