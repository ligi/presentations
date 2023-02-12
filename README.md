---
title: Reveal.js presentation template
description: Reveal.js presentation template running with Jekyll hosted on GitHub Pages.
theme: serif # check out https://revealjs.com/#/themes
transition: slide # none/fade/slide/convex/concave/zoom
permalink: /
---
<section data-markdown><textarea data-template>
  
### revealjs-presentation-template

- Click on [Use the template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) or [fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) this [repo](https://github.com/maehr/revealjs-presentation-template).
- `git submodule add -f https://github.com/hakimel/reveal.js/ assets/vendor/reveal.js`
- `git commit -a`.
- Activate [GitHub Pages](https://pages.github.com/) in repository settings and set [source](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#choosing-a-publishing-source) to `master branch`.

</textarea></section>

<section data-markdown><textarea data-template>
  
### Run it locally

```bash
git submodule add -f https://github.com/hakimel/reveal.js/ assets/vendor/reveal.js
gem install jekyll bundler
bundle exec jekyll serve
```

</textarea></section>

<section data-markdown><textarea data-template>
  
## Headings

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

</textarea></section>

<section data-markdown><textarea data-template>
  
## Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
</textarea></section>

<section data-markdown><textarea data-template>
  
## Links

[I'm an inline-style link](https://www.google.com). [I'm an inline-style link with title](https://www.google.com "Google's Homepage"). [I'm a reference-style link][Arbitrary case-insensitive reference text]. [I'm a relative reference to a repository file](index.md). [You can use numbers for reference-style link definitions][1] Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. http://www.example.com or <http://www.example.com>.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
</textarea></section>

<section data-markdown><textarea data-template>
  
## Images

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
</textarea></section>

<section data-markdown><textarea data-template>
  
### Code and syntax highlight

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

</textarea></section>

<section data-markdown><textarea data-template>
  
## Tables I

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

</textarea></section>

<section data-markdown><textarea data-template>
  
## Tables II

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

</textarea></section>

<section data-markdown><textarea data-template>
  
### Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

</textarea></section>

<section data-markdown><textarea data-template>
  
## Inline HTML

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

</textarea></section>

<section data-markdown><textarea data-template>

## Inline LaTeX

When \\(a \ne 0\\), there are two solutions to \\(ax^2 + bx + c = 0\\) and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

</textarea></section>

<section data-markdown><textarea data-template>
  
### YouTube Videos

<iframe width="840" height="480" src="https://www.youtube.com/embed/HUBNt18RFbo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Just copy and paste the embedded code from [YouTube](https://www.youtube.com/).

</textarea></section>
