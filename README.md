
***

# [:octocat: SNU 2D Programming Tools](https://github.com/seanpm2001/SNU_2D_ProgrammingTools/)

# Plankalkül IDE and compiler

`⌨️ The Plankalkül programming language IDE submodule for SNU Programming Tools (2D Mode)`

## About IDE

The SNU 2D Programming Tools Plankalkül IDE is a web-based IDE that can read, write, and execute programs in the Plankalkül programming language. As like other SNU 2D Programming Tools IDE projects, offline support is also available.

## About Plankalkül and its origin story

Plankalkül is the very first computer programming language, created in 1948 by Konrad Suse, a German computer scientist who also created the first fully functional, turing-complete electronic computer (the Z3) which was created in 1938, and finished in 1941. The programming language was created after Zuse found that programming entirely in machine code is too difficult. The computers and this programming language was created during the era of Nazi Germany, but Zuse was not a supporter of Nazism or Hitler, although he received funding from the Nazi government. In 1945, in post-war Germany, there was too much economic and material deprevation/scarcity for Zuse to build computers. His work went largely unrecognized, with small recognition outside of Germany as early as 1946, with IBM using some of his ideas. It is rumored that Zuse had a meeting with Alan Turing at one point, and by 1949, Zuse was able to start building computers again, and resumed work on the Z4 computer.

`Plankalkül` means `Plan Calculus` or `Formal system` in German.

## Extension

Due to the language pre-dating the standard file system, I have decided to give it the extension `.P` the P stands for Plankalkül, and also Program. It has to be uppercase, as most computers sidn't support lowercase characters until decades later.

## Repository name

It was a struggle to add Plankalkül to the repository name, and it took a couple days of very light thinking to make it look good. I couldn't use `ü` (umlaut) as it isn't an ANSI character. My original plans were either:

- `Plankalk-y-l`
- `Plankalky-l`

as this instance of an umlaut stands for `y:` however, both of these didn't look good, and I went with:

- `Plankalk-u-l`

After creating the repository, I realized Punycode would have worked too, which would have been:

- `Plankalk-xn--tda-l`

Although this is rather complicated.

## Usage

Usage of the Plankalkül IDE is intended for historical/novelty purposes. I don't expect large projects to be made using it.

## Third party Tools

The `Plankalkül-Compiler` by the Free Universaty of Berlin (2000) is expected to be used as an example, and as an extra component.

## Sample source code

Wikipedia example:

The following example defines a function `max3` (in a linear transcription) that calculates the maximum of three variables:

```Plankalkül
P1 max3 (V0[:8.0],V1[:8.0],V2[:8.0]) → R0[:8.0]
max(V0[:8.0],V1[:8.0]) → Z1[:8.0]
max(Z1[:8.0],V2[:8.0]) → R0[:8.0]
END
P2 max (V0[:8.0],V1[:8.0]) → R0[:8.0]
V0[:8.0] → Z1[:8.0]
(Z1[:8.0] < V1[:8.0]) → V1[:8.0] → Z1[:8.0]
Z1[:8.0] → R0[:8.0]
END
```

***

# File info

**File version:** `1 (2023, Monday, July 10th at 3:50 pm PST)`

***
