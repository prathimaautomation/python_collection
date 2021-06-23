
 # Python Data Collections
 - Lists
 - Tuples
 - Dict
 - Sets
 
 - Lists (AKA array in other languages)
 
 - Shopping list - multiple items
 - add, edit, delete, update
 - What is `CRUD` - `Create` `Read` `Update` and `Delete`
 
## Let's create a shopping list
### Syntax [] - name of list =["", "", ""]

`shopping_list = ["apples", "eggs", "dark chocolate", "tea", "bread"]`
             ` #     0         1          2              3      4`
`print(shopping_list)`
#### Checking the type of this data with type()
`print(type(shopping_list))`

#### How can access dark chocolate using the same concept that we learned yesterday INDEXING
`print(shopping_list[1]) # will display eggs`
`print(shopping_list[-1]) # lists the last item -left to right`

#### How to replace an item in the list
`shopping_list[0] = "mango" `
`print(shopping_list)`

#### How can we add an item to our shopping list
`shopping_list.append("Tuna")`
`print(shopping_list)`

#### search python documentation/google and find out how could we delete an item from index 3 from this list
```
shopping_list.pop(3)
print(shopping_list)
```
#### We can have multiple data types in the same list
```
mix_list = [1, 2, 3, "one", "two", "three"]
        #       ints           string
print(type(mix_list))
```
#### What are Tuples and What is the diff between Lists and Tuples
#### Syntax () - name_of_tuple = ("", "","")
```
essentials = ("paracetamol", "Milk", "Butter")
print(essentials)
print(type(essentials))

essentials.pop(1) #AttributeError
print(essentials)
```

# Lists are MUTABLE and Tuples are IMMUTABLE 
<<<<<<< HEAD

# Dictionaries and Sets both are Data collections in Python

## Dict?
### Sets?

# Dict are anotherr way to manage data but can be a little more Dynamic
# Dict work as a KEY AND VALUE
# KEY = THE REFERENCE OF THE OBJECT
# VALUE = WHAT THE DATA STORAGE MECHANISM YOU WISH TO USE
# Dynamic as it we have Lists, and another dict inside a dict
# Syntax -  name = {} we use {} brackets to declare a Dict
#             key = value
```
students_1 = {
    "name": "James",
    "stream": "DevOps",
    "completed_lessons": 4,
    "completed_lessons_names": ["data types", "git and github", "operators", "Lists and Tuples"]
                            #          0             1              2                3
}
```
### Let's check if we have got the syntax right and print the dict
 ` print(students_1)`
 ` print(type(students_1))`
` print(students_1["stream"])` # This is how we can fetch the value saved in the key called stream in our dict
`print(students_1["completed_lessons_names"][1])`
### Could we apply CRUD on a Dict
### print the second last index of key completed_essions_names:[]
`print(students_1["completed_lessons_names"][-2])`

### How can we change the value of any key in our dict
`students_1["completed_lessons"] = 3`
`print(students_1["completed_lessons"])`

###Let's see how can we remove an item from our completed lessons names
`students_1["completed_lessons_names"].remove("operators")`
`print(students_1["completed_lessons_names"])`

### We have some builtin methods that we can use with dict
`print(students_1.keys())`

### To print all the values only values()
`print(students_1.values())`

## Set are also Data collection
### Syntax name = {"", "", ""}
### What is the difference between sets are dict
## Sets are unordered
`shopping_list = ["eggs", "tea", "milk"]`
              `#     0       1      2`
`print(shopping_list)`
`car_part = {"Engine", "Wheels", "Windows"}`
`print(car_part)`
### add an item to Set
`car_part.add("seats")`
### can we remove an item
`car_part.discard("Wheels")`
`print(car_part)`

- Python also has Frozen sets
- Syntax `name = value([1, 2, 3, 4])`
- Create a Frozen-set set and print the values with the type of the sets
=======
>>>>>>> 213a90f3ea5effd844035430c1a679caa31aa5f1
