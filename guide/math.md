# Math support

Neuron's Markdown syntax supports [MathJax](https://www.mathjax.org/).

## LaTeX input

You can type LaTeX code in zettels in three ways:

* **Inline**: by surrounding your code with ``` $...$ ```
* **Block**: by surrounding your code with ``` $$...$$ ```
* **Multi-line block, centered**: 
```markdown
$$    
\begin{split}
    x+1 &= 2 \\
    y+2 &= 3 
\end{split}
$$
```

## Examples

* Inline LaTeX when written as ``` $a^2+b^2$ ``` looks like this: $a^2+b^2$

* Block LaTeX looks like this: $$(A = B) \cong (A \cong B)$$

* The multi-line block example shown above will render like this:
$$    
\begin{split}
    x+1 &= 2 \\
    y+2 &= 3 
\end{split}
$$
