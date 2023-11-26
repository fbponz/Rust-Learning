# Rust concepts
## Variable 
The following code define a immutable variable.
	
	let x = 5; 

if it's required to modify the actual value of the variable, this must be defined like this.

	let mut x = 5;

Rust allows shadowing in their code, that means you can redefine a immutable variable and
you will use the last definition in this scope. The developer cannot redefine the type of the
variable to immutable to mutable in the same scope. 

### Variable types
#### Scalar types


## Constant
Constants are always immutable.

	const nombre_constante: type = {valor};

