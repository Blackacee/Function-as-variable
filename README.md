# Function-as-variable
 
var hashAlgorithm = 'sha1';
var hash;
if ( hashAlgorithm === 'sha1' ) hash = function(value){ /*...*/ };
else if ( hashAlgorithm === 'md5' ) hash = function(value){ /*...*/ };
hash('Fred');

/*hash is a normal variable. It is assigned a reference to a function, after which the function it
references can be invoked using parentheses, just like a normal function declaration.*/
