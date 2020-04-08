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
2. Via colab menu ``File / Save a copy in Drive ...`` create your own persisting version of the notebook
2. Run the first cell to install Julia and IJulia.
3. Change colab runtime to Julia via colab menu ``Runtime/ Change runtime type`` (if julia is already selected, switch to python and back)

#### Note to the user

Since Google does not directly offer Julia-based computing you, have to take care:

- You need to **work from the same notebook** to get access to a Julia 1.3 kernel.
- You might lose connection to the host and, after re-connecting, you might lose your Julia packages that were installed. To tackle this situation, re-run the first cell and proceed with the follow up instructions in the notebook.

#### Blank Notebook

To start a blank julia notebook on Google Colab click https://colab.research.google.com/github/schlichtanders/handson-julia-as-a-glue-language/blob/master/julia_blank.ipynb

## License

This project is licensed under the [MIT License](LICENSE.md).
