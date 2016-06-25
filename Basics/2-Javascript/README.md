## Topic 1- JavaScript Basics
*  [Code Academy - Interactive](http://www.codecademy.com/tracks/javascript)

### Task
####Part 1 - Data Generation

* Create an array of 20 user objects

```
  users = [
   {
    name: name1
    dob: some random date between 1970-2000
    address: {
     street: line1
     landmark: line2
     city: city1
    }
   },{
    name: name2
    dob: some random date between 1970-2000
    address: {
     street: line3
     landmark: line4
     city: city1
    } and so on
  ]
```
* Keep the same city for 5 consecutive users.
* Similar to Array of user objects, create Array of 8 branch objects with branch name and address.
* Each city should have 2 branches - city1 has branch1, branch2. city2 has branch3, branch4 and so on...
* Assign a branch to every user in their own city

####Part 2 - Computations
* Find all users who are less than 30 years of age - print these usernames.
  * User Javascript Data Object to start with
  * In the 2nd iteration use [moment.js](http://momentjs.com/)
* Flip the object Model - Print all cities and all the branches in each city and users in each branch
```
Example
[
  {
    city: city1,
    branches: [
     {
      branch: b1,
      users: [u1, u2, u3]
     },
     {
      branch: b2,
      users: [u5, u6, u7]
     }
    ]
  },
  {
   city: city2,
   branches: [....]
   and so on....
  }
]
```

#### Notes
* All data is to be created programmatically
* Don't use any external libraries in the initial phase
* Write the code in Sublime Text
* Run parts of this in the Chrome Browser Console
* Make this into a simple Node.js project which can be run from the command line
* Save the data and output in different files
* In the 1st iteration
  * Use regular for loops and nothing else
  * Use Javascript's Date function to work on the age computation
* Read about [ES5's native Array iterator methods](https://coderwall.com/p/_ggh2w/the-array-native-every-filter-map-some-foreach-methods)
* In the 2nd iteration
  * use these functions (filter and map) to get your output
  * use [moment.js](http://momentjs.com/) instead of Javascript's Date function
  * do not delete your existing code, just comment it

## Topic 2 - jQuery Basics
* [Code Academy - Interactive](http://www.codecademy.com/tracks/jquery) - Focus on the ajax part of jQuery
  * DOM selectors
  * ajax
  * Difference between generic $.ajax and $.get and $.post
  
### Task
* Go to ```gl.artoo.in/login```
  * Populate the username and password using jQuery. If you can do that, then you should be able to login programatically too!
  * Print out a table of all the tags and their counts in the HTML page e.g. ```<meta> = 1```


## Topic 3 - Chrome Console
* [Code School - Video](https://www.codeschool.com/courses/discover-devtools/videos)
  * Scripts
  * Resources
  * Network

## Advanced Concepts - Read
* [Introduction to Object-Oriented JavaScript - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* Callbacks: http://javascriptissexy.com/understand-javascript-callback-functions-and-use-them/
* Prototypes: Need to find a good link
* Closures: [Robert Nyman’s Blog - Mozilla](http://robertnyman.com/2008/10/09/explaining-javascript-scope-and-closures/)  
* Some of these will be covered in detail in the Web section of Onboarding

### Task
* Create class structure and associated instances for Artoo's team the way you see it. e.g geeks, rainmakers, firefighters, etc and add some fun functions for individuals and teams.
