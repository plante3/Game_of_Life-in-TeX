# Game of Life in TeX
An implementation of the finite state automata *Conway's Game of Life* in the typesetting system TeX.

### What?
<a href="http://www.youtube.com/watch?feature=player_embedded&v=cNi5v6iWGmI" target="_blank"><img src="http://img.youtube.com/vi/cNi5v6iWGmI/0.jpg" 
alt="Demo." width="240" height="180" border="10" /></a>

### Build Instructions:
Download the latest release (`GoL-TeX-V1.1.zip`) and extract the files to a folder. Then run
```
pdftex life.tex
```

### To-do List:
- [x] (2021-3-30) ~~Support parsing of the [*RLE* format](https://www.conwaylife.com/wiki/Run_Length_Encoded)~~.
- [x] (2021-3-30) ~~Support handling of the [generalized life](https://en.wikipedia.org/wiki/Life-like_cellular_automaton#Notation_for_rules)~~.
- [ ] Randomized setup.
- [ ] Implement a toroidal array.

#### How do I view the output?
Scroll *really* fast. Or press page down repeatedly.
