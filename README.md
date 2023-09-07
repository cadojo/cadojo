I love exploring physical concepts through computation, including Julia and Python code. My focus for the last three years of open-source hobby projects has been astrodynamics. At my highest aspiration, I want to create an ecosystem of packages that helps students to explore the solar system without having to learn complicated interfaces! I've also dabbled in other small projects: see my [in-development experimental Python package manager](https://github.com/cadojo/dimples), [`CommonLicenses.jl`](https://github.com/cadojo/CommonLicenses.jl), and my other unpinned [projects](https://loopy.codes/packages)!

### Astrodynamics

`GeneralAstrodynamics.jl` is the largest open source software project I have created. It contains graduate astrodynamics research codes which find halo orbits, and invariant manifolds about those orbits, throughout the solar system. I am working to break this larger package into constituent parts, including `AstrodynamicalModels.jl` and `AstrodynamicalCalculations.jl`. In the future, I hope to add hooks into ephemeris fetching & parsing packages that I have published: `SPICEKernels.jl`, `SPICEBodies.jl`, `HorizonsAPI.jl`, and `HorizonsEphemeris.jl`.

### Developer Tools

Julia's pakage manager allows users to simply replicate environments without much effort. Python is an older language with older package distribution infrastructure. Can Julia's easily-replicatable environments be adapted to Python? Possibly! I'm trying some ideas out in `dimples`. 

See also opinionated (and a bit cursed) namespace hygiene and scoping within `module-hygiene` and `block-scopes`, and Markdown-like admonition blocks (in the style of Julia's in-terminal admonition blocks) in `rich-admonitions`.

When you write open-source computational documents in Julia, consider `CommonLicenses.jl`! This package allows you to easily paste license contents inline, without working about links or manually pasting license text.

### Forward Work

In the coming years, I hope to continue exploring physical concepts through computation with Julia and Python. Along the way, I'll release any potentially useful substantial pieces of code as open source software.

