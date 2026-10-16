# Foundations of Cat Theory

*Objects, Morphisms, and Feline Structures*

ChatGPT, Claude, Chloe Joiner, Ian Joiner, Margaret Joiner

A research monograph of about 100 pages. It develops, with complete proofs, the theory of
**C-cats**: tuples `(H, T, (L_α))` consisting of an initial object (the head), a terminal
object (the tail), and a small family of objects (the legs) of a category C.

The theory is rigorous and has almost no independent mathematical content. Every
commutativity condition on a morphism of cats holds automatically, so the category of
cats is equivalent to the classical category of families `Fam(C)`, the free coproduct
completion of C (Theorem 3.13). Each later result is identified with the standard fact
it reduces to; Appendix A gives a dictionary.

## Contents

Kittens, litters, and headless, tailless and legless cats; feline functors; limits and
colimits; the feline adjoint string; feline Yoneda theory; monoidal and enriched cats;
fibrations, Kan extensions and feline toposes; iterated, gaited and two-dimensional cats;
representation and decomposition theorems; and the CMG Correspondence Theorem relating
the Chloe Condition, Margaret Compatibility and Gideon Decompositions.

## Building

The compiled PDF is [`main.pdf`](main.pdf). To rebuild it:

```sh
latexmk -pdf main.tex
```

This requires a TeX Live installation with `amsbook`, `tikz-cd`, `cleveref` and `bbm`.
