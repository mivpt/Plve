# Plve
Plve: Programming languages ​​are very exciting(...)



 it may be daunting or difficult.
In my opinion, this language is heavily influenced by Python, JavaScript, Go and LISP. But be careful! Don't mistake this language for Python. 😛

Example code:
```
import [:print] from "os"
// or var [:print] = import "os"

print(typeof import) // "import"
print(typeof 1) // "number"

var obj = [
	a: "test",
	b: "f" 
]

fun abc(input): {
    if input:
        return "hi?"
    else:
        return "hi!"
}

var hello = fun: abc(true)
var helloreturnvalue = hello()

print(helloreturnvalue) // hi?

print({
    return 'hello'
}) // hello

var test = fun(num):
    if num < 0:
        -1
    else: (
        if num == 0:
            1
        else:
            (num * self(num - 1))
    )

print(test(5)) // 120

export main = fun: print(test(5))
export test = fun: print("test")
```
