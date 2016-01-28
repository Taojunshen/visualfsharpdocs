# FSharpFunc.op_Implicit<'T,'U> Method (F#)

Convert an value of type **T:System.Converter&#96;2** to a F# first class function value or vice versa.

**Namespace/Module Path:** Microsoft.FSharp.Core

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD

```
// Signatures:
static member op_Implicit : Converter<'T,'U> -> 'T -> 'U
static member op_Implicit : ('T -> 'U) -> Converter<'T,'U>

// Usage:
FSharpFunc.op_Implicit (converter)
FSharpFunc.op_Implicit (func)
```

#### CAPS_PARAMETERS_MD
*converter*
Type: **T:System.Converter&#96;2****&lt;'T,                                                                                       'U&gt;**


The input **T:System.Converter&#96;2** instance.


*func*
Type: **'T -&gt; 'U**


An input function to be converted to a **T:System.Converter&#96;2** instance..



**The result of the conversion.**
## CAPS_REMARKS_MD

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0




## See Also
[Core.FSharpFunc&#60;'T,'U&#62; Class &#40;F&#35;&#41;](Core.FSharpFuncL%27T%2C%27UR+Class+%28F%23%29.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+%28F%23%29.md)
