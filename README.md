Description of the project
The ALX-Holberton B&B sums up the implementation of my four months of studies at the ALX-Holberton School - the fullstack software engineering program. The goal of the project is to deploy a replica of the Airbnb Website using my server. The final version of this project will have:
1. A command interpreter to manipulate data without a visual interface, like a shell (for development and debugging)
2. A website (front-end) with static and dynamic functionalities
3. A comprehensive database to manage the backend functionalities
4. An API that provides a communication interface between the front and backend of the system.
5. General concepts in review
Contents 
AUTHORS	Contains info about authors of the project
base_model.py	Defines BaseModel class (parent class), and methods
user.py	Defines subclass User
amenity.py	Defines subclass Amenity
city.py	Defines subclass City
place.py	Defines subclass Place
review.py	Defines subclass Review
state.py	Defines subclass State
file_storage.py	Creates new instance of class, serializes and deserializes data
console.py	creates object, retrieves object from file, does operations on objects, updates attributes of object and destroys object
test_base_model.py	unittests for base_model
test_user.py	unittests for user
test_amenity.py	unittests for amenity
test_city.py	unittests for city
test_place.py	unittests for place
test_review.py	unittests for review
test_state.py	unittests for state
test_file_storage.py	unittests for file_storage
test_console.py	unittests for console


Usage 
create	Creates object of given class
show	Prints the string representation of an instance based on the class name and id
all	Prints all string representation of all instances based or not on the class name
update	Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file)
destroy	Deletes an instance based on the class name and id (save the change into the JSON file)
count	Retrieve the number of instances of a class
help	Prints information about specific command
quit/ EOF	Exit the program
