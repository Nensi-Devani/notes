# notes
* why BusinessException ?
-> remove multiple catch blocks and also we don't need to remember what exception we wrote for the particular logic

* FileUtil :
-> <T> stands for Type (a generic type parameter), allowing the method to work with any object type while maintaining compile-time type safety.

* [INFO], [ERROR] = logs
* Why my logic does not work -> because it will not be able to find the id of object..
* IdGenerator : (we have getId()) -> to get the id of an object
-> How will it work?
	- Read all objects from the file.
	- Find the last object's ID.
	- Extract the numeric part.
	- Increment it.
	- Return

*** Flow ***
App (Main)
   ↓
LoginController
   ↓
Role detection
   ↓
AdminController / CustomerController / etc
   ↓
Facade (CheckoutFacade)
   ↓
Services
   ↓
Repositories

** create common repo for common methods **

MessageConstants = unwanted messages ...
why keep default constructor empty in models


loat of data - scalability part
duiplicate - restaurant



delivery boy assign idea :
- multiple orders of same pincode.
- pick next order from restaurant in same area where the order has just delivered.


in cart only multiple items from same restaurant should be added.
discount - maha bachat

good flow
solid principle + design pattern


delivery charges

