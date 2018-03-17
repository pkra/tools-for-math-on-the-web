# tools-for-math-on-the-web
Some tools around math on the web


* computational libraries
  * [math.js](http://mathjs.org/)
  * [combinatorics.js](https://github.com/devanp92/combinatorics.js)
  * [vectorious](https://github.com/mateogianolio/vectorious)
  * [numericJS](http://www.numericjs.com/)
  * [Sylvester](https://github.com/jcoglan/sylvester) vector, matrix and geometry library 
  * [MathLib](https://github.com/alawatthe/MathLib)
  * [algebra.js](https://github.com/nicolewhite/algebra.js) Build&solve algebraic equations; includes LaTeX-like output to pass to renderer.
  * [algebrite](https://github.com/davidedc/Algebrite), CAS in JS
  * [simple-statistics](https://github.com/simple-statistics/simple-statistics), statistics in JS
  * [stdlib](https://github.com/stdlib-js/stdlib) "stdlib is a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing applications." 
  * [propelML](http://propelml.org/) "Propel provides a GPU-backed numpy-like infrastructure for scientific computing in JavaScript."
  * [math-expressions](https://github.com/kisonecat/math-expressions) "Math-expressions is client- or server-side JavaScript library for parse expressions like `sin^2 (x^3)` and do some basic computer algebra with them, like symbolic differentiation and numerically identifying equivalent expressions."
* "equation" rendering on the web
  * [MathJax](https://github.com/mathjax/mathjax)
  * [jqmath](http://mathscribe.com/author/jqmath.html) 
  * [mathquill](https://github.com/mathquill/mathquill)
  * [fmath](http://www.fmath.info/)
  * [katex](https://github.com/Khan/KaTeX)
* wysiwyg editors
  * [DraftJS MathJax Plugin](https://github.com/efloti/draft-js-mathjax-plugin)
  * [mathjax-editor](https://github.com/ianlucas/mathjax-editor)
  * [fmath](http://www.fmath.info/)
  * [mathquill](https://github.com/mathquill/mathquill)
  * [ckeditor mathjax latex plugin](http://ckeditor.com/addon/mathjax)
  * [equation editor](https://github.com/camdenre/equation-editor)
  * [Mathslate tinymce/moodle editor](https://github.com/dthies/moodle-editor_tinymce-mathslate), see also [this](https://moodle.org/mod/forum/discuss.php?d=255377). Not quite an "editor": [@efloti's tinymce plugin](https://github.com/efloti/plugin-mathjax-pour-tinymce), [@dthies's tinymce plugin](https://github.com/dthies/tinymce4-mathslate).
  * [fMath](http://fmath.info/), TeX, MathML, also image output; requires Flash, Java.
  * [Wiris](http://www.wiris.net/) both MathML and TeX, also image output
  * other / need review
     * [formulasheet.com](http://formulasheet.com) unclear if available as plugin
     * [hostmath](http://hostmath.com) unclear if available as plugin
     * [mathicando.com](http://www.mathicando.com/) MathML only, unclear if available as plugin
     * [sharemath.com](http://sharemath.com) both MathML and TeX, Flash
     * [mathaway](https://mathway.com/) (internal format: TeX)
     * [latex4technics](http://www.latex4technics.com/)  (internal format: TeX)
  * TeX-like (i.e., trying to be faithful to TeX)
   * [MathJax](https://github.com/mathjax/mathjax)'s TeX input (direct successor of [jsmath](http://www.math.union.edu/~dpvc/jsMath/)).
   * [mathquill](https://github.com/mathquill/mathquill)'s output
   * [KaTeX]()
* Linear input convertors
  * TeX-like input (i.e., trying to be faithful)
    * [MathJax](https://github.com/mathjax/mathjax)
    * [iTeX](https://golem.ph.utexas.edu/~distler/blog/itex2MMLcommands.html)
    * [mathquill](https://github.com/mathquill/mathquill)
    * [katex](https://github.com/Khan/KaTeX)
    * [latex2mathml](https://pypi.python.org/pypi/latex2mathml/1.0.10) (Python)
    * [fMath](http://fmath.info/)
  * ascii/unicode-focused
    * [AsciiMathML](https://github.com/asciimath/asciimathml/)
      * [ascii2mathml](https://github.com/runarberg/ascii2mathml) 
      * [asciimath2tex](https://github.com/christianp/asciimath2tex)
    * [jqmath](http://mathscribe.com/author/jqmath.html)
    * [Microsoft Office linear format](https://support.office.com/en-us/article/Linear-format-equations-and-Math-AutoCorrect-in-Word-2E00618D-B1FD-49D8-8CB4-8D17F25754F8) (see also Murray Sargent's [blog post](http://blogs.msdn.com/b/murrays/archive/2006/09/13/752206.aspx) and [paper](http://www.unicode.org/notes/tn28/UTN28-PlainTextMath-v2.pdf))
    * [CoffeeTeX](https://github.com/kasperpeulen/CoffeeTeX)

* little helpers
  * [Instant Preview for HTML textareas](http://checkmyworking.com/2012/06/instant-mathjax-preview-of-latex-typed-into-html-textareas/) (works with tinymce)
* Visual
  * [latex2js](https://github.com/pyramation/LaTeX2JS) pstricks+variables (cf. [mathapedia](http://www.mathapedia.com/) / latex2html])
  * [unmaintained] [xyjax](https://sonoisa.github.io/xyjax/xyjax.html)
  * [mathbox](https://gitgud.io/unconed/mathbox)
  * [jsxgraph](https://github.com/jsxgraph/jsxgraph) (geometry)
  * [https://github.com/cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) (graph theory)
  * [MathLib](https://github.com/alawatthe/MathLib)
  * [function-plot](https://github.com/maurizzzio/function-plot) "A 2d function plotter powered by D3"
  * [sigma.js](http://sigmajs.org/), "a JavaScript library dedicated to graph drawing. It makes easy to publish networks on Web pages, and allows developers to integrate network exploration in rich Web applications."
* document editors with strong math focus
  * [OERpub editor](http://oerpub.github.io/Aloha-Editor/) open source, Aloha-plugin, not quite wysiwyg, supported by OERpub, ConneXions and others.
  * [StackEdit](https://stackedit.io) In-browser Markdown Editor, with complete MathJax support.
* OCR, handwriting recognition etc
  * [mathcha.io](https://www.mathcha.io/) " Online Mathematics Editor" (noteworthy for diagram support)
  * [Seshat](https://github.com/falvaro/seshat) Handwritten math expression parser
  * [MyScript Web Equation](http://webdemo.myscript.com/#/demo/equation), using handwriting recognition, LaTeX, MathML output as well as Desmos and Wolfram Alpha integration. The technology can be integrated into iOS and Android apps, see [1](https://itunes.apple.com/app/myscript-mathpad/id674996719), [2](https://itunes.apple.com/us/app/math-ink/id596393352). 

* fringe tools 
  * [pseudocode.js](https://github.com/tatetian/pseudocode.js), a JS library similar to the TeX package [algorithms](https://ctan.org/pkg/algorithms)
