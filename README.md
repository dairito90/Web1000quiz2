# Web1000quiz2
Instructions: create a new repository called ng-ds-test. Within this repo, create a README.md file. Copy and paste all of these questions into this README file and answer them.

Name and describe the two main operations of a stack (to add and remove data).
Is a data structure where the last thing to come in is the first one to go on.
push: to enter data.
pop: to remove data.


Name and describe the two main operations of a queue (to add and remove data).
dequeue: to remove data.
enqueue: to add data.


Draw the tree resulting from adding the following sequence of numbers to an empty tree: 30, 45, 15, 10, 50, 40, 20, 27
          -----------30-----------
          ------15--------45
          10-----20-----40----50----
          ---------27


Is this tree balanced? If not, which rotation needs to be done? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))
is balanced.


Now add 29. Is the tree balanced? If not, which rotation needs to be done? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))
not balanced.
leftRotation(10).



Consider the following tree:
------5
---2-----8
-1--3

Now add 0 to the tree. Which one is the first node to go out of balance?
-------5
-----2-----8
-1--3
0
-the first node to go out is 0.




How do you fix this node? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))

leftRotation.





What are the four main steps of mergesort?
-split array in two parts.
-mergesort left half.
-mergesort right half.
-join the two arrays.




Say you have a program which handles the login queue to a game server. The game server is able to log in one person every one second. Assume that one second must elapse after a person logs in with an empty queue before they are removed from the queue. Draw the state of the queue at 12:00:06, considering the following sequence of events:

At 12:00:00 Hades logs in
At 12:00:00 Ares logs in
At 12:00:00 Zeus logs in
At 12:00:00 Buzz Light Year logs in
At 12:00:02 Kanye West logs in
At 12:00:03 Taylor Swift logs in
At 12:00:03 Darkwing Duck logs in
At 12:00:04 Evil Mickey logs in.

At 12:00:06 Dairon Rodriguez logs out.

What is an angular directive?

-the angular directive are extended attributes whit the prefix ng-ds-test,
its the whole app itself. Initialize a angular app.





When specifying an angular directive, you write a function which must return an object called:
a. Directive Constructor --> correct.
b. Fidel y Chavez Object
c. Directive Definition object
d. Directive Object





What is the relationship between html, the $scope construct, and angular expressions? (Expressions are the ones that are written like so: {{quote}} ).
$scope Constructor connects the application controller and the view (html).Both controllers and directives have reference to the scope and expressions are a angularjs code.



In order to send ajax requests in Angular, the most accepted programming convention is to create an angular:
a. Module
b. Service
c. Controller
d. $http --> correct.

In order to create a service, you must use the following angular function:
a. angularApp.controller
b. angularApp.module --> correct.
c. angularApp.directive
d. angularApp.factory

Do this exercise: https://github.com/Real-Skill/angular-exercises/tree/exercise1 You will need to run git checkout exercise1 in addition to the commands listed in that readme. You do not need to run grunt karma.
