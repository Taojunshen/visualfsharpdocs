# FSharpFunc.Adapt<'T1,'T2,'T3,'T4,'U> Method (F#)

Adapt an F# first class function value to be an optimized function value that can accept four curried arguments without intervening execution.

**Namespace/Module Path:** Microsoft.FSharp.Core.OptimizedClosures

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD

```
// Signature:
static member FSharpFunc.Adapt : ('T1 -> 'T2 -> 'T3 -> 'T4 -> 'U) -> FSharpFunc<'T1,'T2,'T3,'T4,'U>

// Usage:
FSharpFunc.Adapt (func)
```

#### CAPS_PARAMETERS_MD
*func*
Type: **'T1 -&gt; 'T2 -&gt; 'T3 -&gt; 'T4 -&gt; 'U**


The input function.



**The optimized function.**
## CAPS_REMARKS_MD

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[OptimizedClosures.FSharpFunc&#60;'T1,'T2,'T3,'T4,'U&#62; Class &#40;F&#35;&#41;](OptimizedClosures.FSharpFuncL%27T1%2C%27T2%2C%27T3%2C%27T4%2C%27UR+Class+%28F%23%29.md)

[Core.OptimizedClosures Module &#40;F&#35;&#41;](Core.OptimizedClosures+Module+%28F%23%29.md)
