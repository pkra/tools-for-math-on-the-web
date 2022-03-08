# Tools for math on the web

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
  * [KAS](https://github.com/Khan/KAS) "lightweight JavaScript CAS"
   * [Polynomial.js](https://github.com/infusion/Polynomial.js) "A JavaScript library to work with polynomials"
  * [simple-statistics](https://github.com/simple-statistics/simple-statistics), statistics in JS
  * [stdlib](https://github.com/stdlib-js/stdlib) "stdlib is a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing applications." 
  * [propelML](http://propelml.org/) "Propel provides a GPU-backed numpy-like infrastructure for scientific computing in JavaScript."
  * [math-expressions](https://github.com/kisonecat/math-expressions) "Math-expressions is client- or server-side JavaScript library for parse expressions like `sin^2 (x^3)` and do some basic computer algebra with them, like symbolic differentiation and numerically identifying equivalent expressions."
  * [geometric](https://github.com/HarryStevens/geometric), "A JavaScript library for doing geometry." 
  * [TheoremJS](https://github.com/arguiot/TheoremJS), "A Math library for computation in JavaScript"
* editors (wysiwyg etc)
  * [mathlive](https://mathlive.io) 
  * [DraftJS MathJax Plugin](https://github.com/efloti/draft-js-mathjax-plugin)
  * [mathjax-editor](https://github.com/ianlucas/mathjax-editor)
  * [fmath](http://www.fmath.info/)
  * [mathquill](https://github.com/mathquill/mathquill)
  * [ckeditor mathjax latex plugin](http://ckeditor.com/addon/mathjax)
  * [equation editor](https://github.com/camdenre/equation-editor)
  * [Mathslate tinymce/moodle editor](https://github.com/dthies/moodle-editor_tinymce-mathslate), see also [this](https://moodle.org/mod/forum/discuss.php?d=255377). Not quite an "editor": [@efloti's tinymce plugin](https://github.com/efloti/plugin-mathjax-pour-tinymce), [@dthies's tinymce plugin](https://github.com/dthies/tinymce4-mathslate).
  * [fMath](http://fmath.info/), TeX, MathML, also image output; requires Flash, Java.
  * [Wiris](http://www.wiris.net/) both MathML and TeX, also image output
  * [Texthelp EquatIO](https://www.texthelp.com/en-us/products/equatio/), "easily add equations, formulas, graphs and more to g suite for education apps and microsoft word" (handwriting, speech, voicing in Read&Write using speech-rule-engine)
  * [MathYlem](https://ylemkimon.github.io/mathylem/) 
  * [guppy](https://github.com/daniel3735928559/guppy)
  * other / need review
     * [formulasheet.com](http://formulasheet.com) unclear if available as plugin
     * [hostmath](http://hostmath.com) unclear if available as plugin
     * [mathicando.com](http://www.mathicando.com/) MathML only, unclear if available as plugin
     * [sharemath.com](http://sharemath.com) both MathML and TeX, Flash
     * [mathaway](https://mathway.com/) (internal format: TeX)
     * [latex4technics](http://www.latex4technics.com/)  (internal format: TeX) 
* TeX-like output (i.e., trying to be faithful to Appendix G, TeX book)
   * [MathJax](https://github.com/mathjax/mathjax)'s TeX input (direct successor of [jsmath](http://www.math.union.edu/~dpvc/jsMath/)).
   * [KaTeX](https://github.com/Khan/KaTeX/)
* equation convertors (with repetitions)
  * output: visual
    * [MathJax](https://github.com/mathjax/mathjax)
    * [jqmath](http://mathscribe.com/author/jqmath.html) 
    * [mathquill](https://github.com/mathquill/mathquill)
    * [fmath](http://www.fmath.info/)
    * [mathematical](https://github.com/gjtorikian/mathematical) A wrapper around Lasem and mtex2MML to generate SVG, PNG, MathML. 
    * [katex](https://github.com/Khan/KaTeX)
    * [math-ml](https://github.com/pshihn/math-ml), web components using simple CSS, early beta
  * input: TeX-like (i.e., trying to be faithful)
    * [MathJax](https://github.com/mathjax/mathjax)
    * [iTeX](https://golem.ph.utexas.edu/~distler/blog/itex2MMLcommands.html)
    * [mathquill](https://github.com/mathquill/mathquill)
    * [katex](https://github.com/Khan/KaTeX)
    * [latex2mathml](https://pypi.python.org/pypi/latex2mathml/1.0.10) (Python)
    * [fMath](http://fmath.info/)
  * input: ascii/unicode-focused
    * [AsciiMathML](https://github.com/asciimath/asciimathml/)
      * [ascii2mathml](https://github.com/runarberg/ascii2mathml) 
      * [asciimath2tex](https://github.com/christianp/asciimath2tex)
    * [jqmath](http://mathscribe.com/author/jqmath.html)
    * [Microsoft Office linear format](https://support.office.com/en-us/article/Linear-format-equations-and-Math-AutoCorrect-in-Word-2E00618D-B1FD-49D8-8CB4-8D17F25754F8) (see also Murray Sargent's [blog post](http://blogs.msdn.com/b/murrays/archive/2006/09/13/752206.aspx) and [paper](http://www.unicode.org/notes/tn28/UTN28-PlainTextMath-v2.pdf))
    * [CoffeeTeX](https://github.com/kasperpeulen/CoffeeTeX)
    * [mathup](https://github.com/runarberg/mathup) asciimath-like to MathML
  * output: textual descriptions
    * [speech-rule-engine](https://github.com/zorkow/speech-rule-engine/) for MathML to textual descriptions 
      * also part of the [MathJax Accessibility Extensions](https://docs.mathjax.org/en/latest/options/extensions/a11y-extensions.html#a11y-extensions).
     * [Aster](https://github.com/tvraman/aster-math) (for TeX documents)
  * output: Braille
    * [speech-rule-engine](https://github.com/zorkow/speech-rule-engine/): MathML to Nemeth 
    * [MML2Nem](https://github.com/SusanJ/MML2Nem):  MathML to Nemeth (and back [Baknem](https://github.com/SusanJ/Baknem))
    * [mathml2braille](https://github.com/civodulab/mathml2braille) JS, converts MathML to fr, nemeth or ueb.
    * [mathml2asciimath](https://github.com/learningobjectsinc/mathml-to-asciimath) JS, converts a subset of MathML to asciimath
* "Unicode authoring"
  * [tex-to-unicode browser extension](https://github.com/golopot/tex-to-unicode) (the underlying lib can be used separately)
  * [unicodeIt](https://github.com/svenkreiss/unicodeit)
* little helpers
  * [Instant Preview for HTML textareas](http://checkmyworking.com/2012/06/instant-mathjax-preview-of-latex-typed-into-html-textareas/) (works with tinymce)
  * [TeX all the things](https://github.com/emichael/texthings), Chrome extension injecting MathJax
  * [mathml-block](https://github.com/adamsilverstein/mathml-block), "A MathML block for the WordPress block editor (Gutenberg)" (but really a 'mathjax block' since MathML is neither used as in- or output).
* drawing, plotting etc. 
  * [latex2js](https://github.com/pyramation/LaTeX2JS) pstricks+variables (cf. [mathapedia](http://www.mathapedia.com/) / latex2html])
  * [unmaintained] [xyjax](https://sonoisa.github.io/xyjax/xyjax.html)
  * [mathbox](https://gitgud.io/unconed/mathbox)
  * [jsxgraph](https://github.com/jsxgraph/jsxgraph) (geometry)
  * [https://github.com/cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) (graph theory)
  * [MathLib](https://github.com/alawatthe/MathLib)
  * [function-plot](https://github.com/maurizzzio/function-plot) "A 2d function plotter powered by D3"
  * [sigma.js](http://sigmajs.org/), "a JavaScript library dedicated to graph drawing. It makes easy to publish networks on Web pages, and allows developers to integrate network exploration in rich Web applications."
  * [pts](https://ptsjs.org/)"Pts enables you to compose and express what you see in your mind's eyes — points as ideas, shapes, colors, motions, interactions, and more."
  * [jsx-tikzcd](https://github.com/yishn/jsx-tikzcd) tikzcd diagrams with JSX.
  * [tikzcd-editor](https://github.com/yishn/tikzcd-editor) visual editor for tikzcd.
  * [tikzjax](https://github.com/kisonecat/tikzjax) TikZ running under WebAssembly in the browser
  * [Descartes](https://github.com/arguiot/Descartes), "A small plotting JavaScript library, made for TheoremJS"
* document editors with strong math focus
  * [OERpub editor](http://oerpub.github.io/Aloha-Editor/) open source, Aloha-plugin, not quite wysiwyg, supported by OERpub, ConneXions and others.
  * [StackEdit](https://stackedit.io) In-browser Markdown Editor, with complete MathJax support.
* OCR, handwriting recognition etc
  * [mathcha.io](https://www.mathcha.io/) " Online Mathematics Editor" (noteworthy for diagram support)
  * [Seshat](https://github.com/falvaro/seshat) Handwritten math expression parser
  * [MyScript Web Equation](http://webdemo.myscript.com/#/demo/equation), using handwriting recognition, LaTeX, MathML output as well as Desmos and Wolfram Alpha integration. The technology can be integrated into iOS and Android apps, see [1](https://itunes.apple.com/app/myscript-mathpad/id674996719), [2](https://itunes.apple.com/us/app/math-ink/id596393352). 
* fringe tools 
  * [pseudocode.js](https://github.com/tatetian/pseudocode.js), a JS library similar to the TeX package [algorithms](https://ctan.org/pkg/algorithms), compatible with KaTeX and MathJax (both v2 and v3)
* not-actually-web tools
  * [iosMath](https://github.com/kostub/iosMath) TeX equation renderer for iOS and MacOS.
  * [CSharpMath](https://github.com/verybadcat/CSharpMath) C# port of iosMath.
  * [iOSLaTeX](https://github.com/TeamSlader/iOSLaTeX), mathjax-based rendering for iOS apps.
  * [mathtype_to_mathml](https://github.com/jure/mathtype_to_mathml), METF to MathML convertor
* content production tools
  * [mathtype (convertor)](https://github.com/jure/mathtype), ruby gem converting proprietary MathType binary equations into an XML form.
  * [math-api](https://github.com/chialab/math-api) REST API based on mathjax-node (serverless, AWS-ready)
  * [mathjax-server](https://github.com/tiarno/mathjax-server) simple server front-end for mathjax-node
  * [pb-mathjax](https://github.com/pressbooks/pb-mathjax), <q>a replacement for https://wp.com/latex.php but instead of LaTeX, it uses MathJax</q>.
* iOS, Android development
  * [MathView](https://github.com/jianzhongli/MathView) third-party library for Android app development
* LMS, Assessment etc
  * [Numbas](https://www.numbas.org.uk/) ([github](https://github.com/numbas/Numbas/)) Really versatile maths e-assessment. 
  * [IMathAS](https://github.com/drlippman/IMathAS) An Internet Mathematics Assessment System.
  * [WeBWork](https://webwork.maa.org/wiki/WeBWorK_Main_Page) ([github](https://github.com/openwebwork))
* physical world
  * [paper plotter](https://felixboiii.github.io/paper-plotter/) 3D plots out of paper (take a function, generates PDF for stackable printout)      
