1.- 

2.- bar, bar, undefined, bar.
	
	The undefined result is due to the fact that the "this.foo" in the internal function works as a local variable, which is never declared

3.- In other languages, you can use the namespace keyword. With this you can have private methods, that are call by public methods.

4.- Arguments is a local variable inside every function. and it contains every argument, that is pass to a function, is specially useful when we talk about functions with variable number of arguments.

5.- Returns undefined because at the moment of call the bar method, baz was not defined.

6.- '1undefined'. At the moment of concatenate the 'x' variable with a method f which doesn't have a return type, it simple converts x which value was 1 to a string
and add the word 'undefined'.

7.- 

8.- The code should be executed in strict mode. The progammer can't use all the facilites that javascript gives them, like use undeclared variables or skips semicolons, ets...

9.-(i)=> i * 2;

10.-    function Logger(level){
        this.level = level
    }
    
    Logger.prototype.log = function(msg){
    	this.level = 'INFO';
        console.log(this.level + ' ' +msg);
    }

	Logger.prototype.log(" message");

11.- In prototypal inheritance, objects inherit directly from other objects, instead of the classical where classes are the ones who inherits from other classes.