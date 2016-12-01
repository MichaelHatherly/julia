# Julia Documentation README

Julia's documentation is written in Markdown. A reference of all supported syntax can
be found at http://docs.julialang.org/en/latest/manual/documentation/#markdown-syntax.

## Requirements

The only dependancy required to build Julia's documentation, apart from Julia
itself, is the [Documenter.jl](https://github.com/JuliaDocs/Documenter.jl). This
package is available in the offical METADATA.jl repository and can be installed
via `Pkg.add("Documenter")`.

## Building

To build Julia's documentation run

```sh
$ make docs
```

which will generate a complete HTML website in the `doc/_build/` directory.

