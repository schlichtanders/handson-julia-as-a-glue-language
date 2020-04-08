# handson-julia-as-a-glue-language
Get to know how powerful Julia is in glueing different systems together

<a name="logo"/>
<div align="center">
<a href="https://julialang.org/" target="_blank">
<img src="https://julialang.org/images/logo_hires.png" alt="Julia Logo" width="210" height="142"></img>
</a>
</div>
<br/>A notebook for running Julia 1.3.1 on Google Colab using the IJulia package.

## Prerequisites

A Google account, that's all.

## Using the Notebook

A step-by-step guide that tells you how to get the environment running:
1. Open the Jupyter notebook julia_as_a_glue_language.ipynb in Google Colab by clicking https://colab.research.google.com/github/schlichtanders/handson-julia-as-a-glue-language/blob/master/julia_as_a_glue_language.ipynb
2. Via colab menu ``File / Save a copy in Drive ...`` create your own persisting version of the notebook. Continue on the new copy and close the initial colab.
3. Run the first cell to install Julia and IJulia.
4. Change colab runtime to Julia via colab menu ``Runtime / Change runtime type`` (if julia is already selected, switch to python and back)

#### Note to the user

Since Google does not directly offer Julia-based computing you, have to take care:

- You need to **work from the same notebook** to get access to a Julia 1.3 kernel.
- You might lose connection to the host and, after re-connecting, you might lose your Julia packages that were installed. To tackle this situation, re-run the first cell and proceed with the follow up instructions in the notebook.

#### Blank Notebook

To start a blank julia notebook on Google Colab click https://colab.research.google.com/github/schlichtanders/handson-julia-as-a-glue-language/blob/master/julia_blank.ipynb and follow the same instructions as above.

## Why Julia?

**Why was Julia created?**
Definitely read this now impressively old post by Julia founders by Jeff Bezanson, Stefan Karpinski, Viral B. Shah, and Alan Edelman https://julialang.org/blog/2012/02/why-we-created-julia/.

Here my favourite passage

> We want the speed of C with the dynamism of Ruby. We want a language that's homoiconic, with true macros like Lisp, but with obvious, familiar mathematical notation like Matlab. We want something as usable for general programming as Python, as easy for statistics as R, as natural for string processing as Perl, as powerful for linear algebra as Matlab, as good at gluing programs together as the shell. Something that is dirt simple to learn, yet keeps the most serious hackers happy. We want it interactive and we want it compiled.

**Why this needs to be an extra language?** Why cannot Python be made that fast for instance?
Checkout the official compact answer to this in the julia manual F&Q https://docs.julialang.org/en/v1/manual/faq/#Why-don't-you-compile-Matlab/Python/R/%E2%80%A6-code-to-Julia?-1

Here my favourite passage

> Julia's advantage is that good performance is not limited to a small subset of “built-in” types and operations, and one can write high-level type-generic code that works on arbitrary user-defined types while remaining fast and memory-efficient. Types in languages like Python simply don't provide enough information to the compiler for similar capabilities, so as soon as you used those languages as a Julia front-end you would be stuck.


Here my favourite passage

    We want the speed of C with the dynamism of Ruby. We want a language that's homoiconic, 
    with true macros like Lisp, but with obvious, familiar mathematical notation like Matlab.
    We want something as usable for general programming as Python, as easy for statistics as R,
    as natural for string processing as Perl, as powerful for linear algebra as Matlab, 
    as good at gluing programs together as the shell. Something that is dirt simple to learn, 
    yet keeps the most serious hackers happy. We want it interactive and we want it compiled.

**Why this needs to be an extra language?** Why cannot Python be made that fast for instance?
Checkout the official compact answer to this in the julia manual F&Q https://docs.julialang.org/en/v1/manual/faq/#Why-don't-you-compile-Matlab/Python/R/%E2%80%A6-code-to-Julia?-1

Here my favourite passage

    Julia's advantage is that good performance is not limited to a small subset of “built-in” 
    types and operations, and one can write high-level type-generic code that works on arbitrary 
    user-defined types while remaining fast and memory-efficient.
    Types in languages like Python simply don't provide enough information to the compiler for 
    similar capabilities, so as soon as you used those languages as a Julia front-end you would be stuck.


## License

This project is licensed under the [MIT License](LICENSE.md).
