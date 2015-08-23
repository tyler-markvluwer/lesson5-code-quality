# lesson5-code-quality
This is not 381, but we will do our best

We will not go over all of the materials of EECS 381, and they are not all relevant in web dev either. What we will do though, is emphasize the basics. If someone on your team has taken the class or is good with code quality then consult them often. This README is currently incomplete, but will be updated after the lecture.

## Use Classes:
This is Coffeescript and is very class friendly. As you plan your project think of what classes and methods might be useful, and the decide on the INTERFACE ahead of time. This way your teammates can proceed with their own coding, and when your code is complete, the project should fall right into place.

## Plan ahead:
Figure out what classes you will need, what functionality you will need, and how the work will be divided. If you can understand the classes ahead of time and divide work on a class-by-class basis, your team will be able to work indepently of each other, and you will be able to work faster. Changes to design part way through the project will likely cause hiccups in multiple places. This will probably happen anyways, but try to minimize it.

## When thinking about the app, separate different groups of functionality
You should be able to separate the things which handle the actual data of the app (the model), the view of the app (view) and the interface layer which takes user input and modifies the data (controller). You don't have to follow a strict MVC pattern, but you shouldn't have classes which do more than 1 of the responsibilities.

## Complete and test your functionality first
The actual visual design and user interaction portions are best handled last. I know it sucks to not see things rendered on the screen as you work on them, but this is the best way to work. This way you can know for a fact what your data-level interface is before you even start working on rendering. This is also a good safeguard for us so that someone else can start on the UI portion if you are only able to complete the data portion during the course of the semester.
