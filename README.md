Heading  ckv
===========

This is a simple config syntax. The ckv is an embedable parser that can return to you a 
very basic char \*\* array. You pass that char\*\* array to any cvk function and it will return to you
a char \* that has either the key or the value. If that key is nested, then the 
namespace leading up to that key is included in the keyname. This is only if you are asking for the key, 
otherwise the value is returned.
