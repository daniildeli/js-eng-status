#Worklogs

##2019-February-15

* *Theory*
	* Advanced data structures: https://medium.com/dev-blogs/ds-with-js-stack-queue-d91fc8cea7a3;
	* EloquentJS: functions, data structures, higher-order functions. (Chapter 3 - 5);

* *Practise*
	* Tasks on Eloquentjavascript (chapter 3 - 5). Code here: https://github.com/daniildeli/EloquentJS;

	* Troubles with next exercises:
		* chapter-04 - compare.js;
		* chapter-04 - list.js;
		* chapter-05 - age.js

##2019-February-14

* *Theory*
	* Analyze information about values, types, operators and program structure on Eloquentjavascript (https://karmazzin.gitbooks.io/eloquentjavascript_ru/content/chapters/chapter1.html and https://karmazzin.gitbooks.io/eloquentjavascript_ru/content/chapters/chapter2.html);
	* Memory managemament in js

* *Practise*
	* Complited tasks on Eloquentjavascript (chapter 2). Code here: https://github.com/daniildeli/EloquentJS
	* Looked on memory, stack and event loop in js (https://github.com/daniildeli/JStrainings/tree/master/test). This video seems quite informative: https://www.youtube.com/watch?v=8cV4ZvHXQL4

##2019-February-13

* *Theory*
	* Investigated information about type conversion, conditionals and loops

* *Practise*
	* Working with data types, conditionals and loops. (https://github.com/daniildeli/JStrainings/tree/master/JS/type_condition_loops)
	
*  There are a few moments that seems a little weird for me:
	* Type conversion: 
		* {} + [] + {} + [1] ==> "[object Object][object Object]1";
		* ! + [] + [] + ![] ==> "truefalse";
		* {} + [] ==> "[object Object]";	 
		* +{} + [] ==> "NaN";  
	* for of: Can we use it for objects like:
		let obj = {
		  a: 1,
		  b: 2,
		  c: 3
		}
		
		for (let i of obj){
		  console.log(i);
		}

		==> TypeError

##2019-February-12

* *Theory*
	* Investigated information on MDN (Numbers, Strings, Arrays, Objects, Date, Functions)

* *Practise*
	* Working with parameters and methods on test scripts. (https://github.com/daniildeli/JStrainings/tree/master/JS/MDN)

##2019-February-11

* *Theory*
	* Finished online courses about Git: How to Use Git and GitHub (https://www.udacity.com/course/how-to-use-git-and-github--ud775), Version Control with Git (https://www.udacity.com/course/version-control-with-git--ud123)
	* Javascripting: variables, string, numbers, if statements, loops, arays, objects, functions, scope

* *Practise*
	* Test actions by the course Version Control with Git (https://www.udacity.com/course/version-control-with-git--ud123)
	* Javascripting: installed and completed all exercises, code here: https://github.com/daniildeli/JStrainings/tree/master/JS/javascripting

##2019-February-08

* *Theory*
	* How to Use Git and GitHub (https://www.udacity.com/course/how-to-use-git-and-github--ud775)
	* NPM docs https://docs.npmjs.com

* *Practise*
	* Working with ESLint: configuration scripts and config. file, added necessary packages;
	* Working with Git: log, diff. Created several test branches and merge them.


##2015-July-29

* *Theory*
	* Canvas [Painting](http://eloquentjavascript.net/19_paint.html)

* *Practise*
	* Canvas [Paint Project](https://github.com/olehkazban/Project-Paint)

* *Miscellaneous*
	* Sinon [FakeXMLHttpRequest](http://sinonjs.org/docs/#FakeXMLHttpRequest)
	* Sinon [fakeServer](http://sinonjs.org/docs/#fakeServer)

