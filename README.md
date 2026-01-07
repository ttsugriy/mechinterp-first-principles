# First Principles of Mechanistic Interpretability

A 15-chapter book building deep understanding of mechanistic interpretability from the ground up.

## What Is This?

This is a first-principles exploration of **mechanistic interpretability** — the project of reverse engineering neural networks to understand *how* they work, not just *that* they work.

Neural networks discover algorithms we didn't teach them. A small network trained on modular arithmetic invented Fourier transforms. Language models develop circuits for grammar, reasoning, and knowledge retrieval. We built these systems, but we don't understand what they've learned.

This book aims to change that, one concept at a time.

## The Approach

We use two guiding frameworks:

1. **Polya's Problem-Solving Method** — Understand the problem before devising solutions. Verify through intervention. Always ask "what would make this explanation wrong?"

2. **Performance Engineering Mindset** — You can't optimize what you don't understand. Measure before you interpret. Never trust unvalidated claims.

## Book Structure

### Arc I: Foundations
*What are we trying to understand?*

1. [Why Reverse Engineer Neural Networks?](chapters/01-why-reverse-engineer.qmd)
2. [Transformers as Matrix Multiplication Machines](chapters/02-transformers.qmd)
3. [The Residual Stream](chapters/03-residual-stream.qmd)
4. [Activations as Geometry](chapters/04-geometry.qmd)

### Arc II: Core Theory
*The fundamental concepts*

5. [Features: The Atoms of Representation](chapters/05-features.qmd)
6. [The Superposition Hypothesis](chapters/06-superposition.qmd)
7. [Toy Models: Understanding Superposition in Miniature](chapters/07-toy-models.qmd)
8. [Circuits: The Molecules of Computation](chapters/08-circuits.qmd)

### Arc III: Techniques
*The tools of the trade*

9. [Sparse Autoencoders](chapters/09-sparse-autoencoders.qmd)
10. [Attribution: Working Backwards](chapters/10-attribution.qmd)
11. [Activation Patching](chapters/11-patching.qmd)
12. [Ablation Studies](chapters/12-ablation.qmd)

### Arc IV: Synthesis
*Putting it all together*

13. [Case Study: Induction Heads](chapters/13-induction-heads.qmd)
14. [Open Problems](chapters/14-open-problems.qmd)
15. [Building Intuition: A Practice Regime](chapters/15-practice-regime.qmd)

## Reading Online

This book is published at: **https://ttsugriy.github.io/mechinterp-first-principles/**

The series is also available on [Software Bits](https://softwarebits.substack.com/) on Substack.

## Building Locally

This is a [Quarto](https://quarto.org/) book. To build locally:

```bash
# Install Quarto first: https://quarto.org/docs/get-started/

# Clone the repo
git clone https://github.com/ttsugriy/mechinterp-first-principles.git
cd mechinterp-first-principles

# Preview with live reload
quarto preview

# Or build static site
quarto render
```

## Contributing

Found a typo? Have a suggestion? Open an issue or PR.

For larger contributions or discussions, please open an issue first.

## License

Content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Code examples are MIT licensed.

## Acknowledgments

This book draws heavily on the work of:

- [Anthropic's Transformer Circuits Thread](https://transformer-circuits.pub/)
- [Neel Nanda's interpretability resources](https://www.neelnanda.io/mechanistic-interpretability/glossary)
- [ARENA curriculum](https://www.arena.education/curriculum)
- [Chris Olah's foundational work](https://colah.github.io/)
