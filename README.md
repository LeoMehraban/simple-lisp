# Simple Lisp
Simple Lisp is a version of lisp. files are `.slisp` files. and code looks like this

` (defun say_hello (person) (print (format "Hello %s",person))) `
it's just a simple version of lisp. no new marcos or whatever. just look up lisp and you can find a good tutorial.

NOTE: thare is not much of a system library around Simple Lisp. thare are only `(defun )` ,`(defvar )`,`(setq )`,`(print )`,`(read)`,`(if )` and math openations +,-,*,/,%. also thate is the `(length )` function. for getting the length of lists

the rest of the functions you have to create yourself.

datatypes: thare are are lists, nums, strings, and chars.
## installing
`$ npm install simple_lisp -g`
NOTE: not publisd to npm yet. soon you can run this command

## running
`$ simple_lisp path/to/file.slisp`

### see you next time!!!