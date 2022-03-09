# luve
___
Need to have a variable unused but still need it to exist?
Use LUVE!
```go
a := 9
luve.Luve(a)
// now the compiler wont complain!
```
**Seriously , that's it 🤯**
if you want the version of luve your using , use `LuveVer`.
## EXAMPLE
_______________
```go
[...]
import "github.com/Pandademic/luve"
a := 9
b := 10
luve.Luve(a,b)
fmt.Println("luve version:"+luve.LuveVer)
[...]
```
