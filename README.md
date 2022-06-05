# To-Do List
This is a to-do list madde for tracking your goals. You can add, cross-out, and remove list items from it as needed to stay organized.
**Link to project:** https://manifestlist.netlify.app
![listimg](https://user-images.githubusercontent.com/102004376/165017824-5459ec5c-00cf-4df6-990e-e1ec631c1447.JPG)


## How It's Made:
**Tech used:** HTML, CSS, JavaScript

To build this I first focused on creating constants for variables I would be using to reference the DOM. From there I focused on creating functions that followed how the user would be interacting with the code. This allowed me start with creating a function that would create li elements in the DOM. Next was the function to click on an li to cross out an item. From there it was a button to clear crossed out items and finally was a button to clear all at once. Moving in this order not only kept the code cohesive and organized, it also made easier to stay on task as I tackled each function. 

This project was updated to be fullstack express. I adjusted the app so that new items add to to the list would be posted to mongodb and then rendered after. I also included a property of checked that was sent up with an app.put request in order to clear any crossed out items.

## Lessons Learned:

It took a second to switch my thinking over to CRUD and MongoDb when working on making this app fullstack. I learned how to include additional properties with app.post and got to know the importance of console logging elements when trying to target them in the program.


## Examples:
Take a look at these couple examples that I have in my own portfolio:

**Slot Machine:** https://github.com/Resilient-Labs/slot-machine-2019-week05

