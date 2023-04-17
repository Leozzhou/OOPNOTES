# Object Oriented Programming Notes 1

I think OOP is awesome :D

##### Example of a Class
```python
class Person: 
    def __init__(self, name):
        self.name = name
        
    def __str__(self):
        return f"Person Object called: {self.name}"
        
    def __repr__(self)
        return self.__str__()

```

## Definitions 
- Encapsulation
    - Encapsulation is the act of information hiding which is restricting the access to classes and objects’ certain attributes and methods
- Polymorphism
    - Polymorphism is a method that can be used across different classes and object that is dependent on the parameters
- Override
    - Overriding is the action of two methods with the same method name and parameters

#### Importance of Encapsulation:
```python
class Student:
  def __init__(self,nameF, nameL, num):
    self.firstName = nameF
    self.lastName = nameL
    self.__studentNumber = num

#end of Student

s1 = Student("Mr.", "Park", 10)
print(s1.firstName) # Returns/Outputs “Mr.”

s1.firstName = "Ms."
print(s1.firstName) # Returns/Outputs “Ms.”
```
The reason for encapsulation is for data protection and restricting certain methods to be callable
##### Example of Encapsulation:
```python
class Student:
	def __init__(self,nameF,nameL,num):
		self.firstName = nameF
		self.lastName = nameL
		self.__studentNumber = num
	def __getStudentNumber(self):
		return self.__studentNumber
```

#### Polymorphism objective:
1. Different classes can have the same named methods 
2. a set of inherited classes can have the same methods 



