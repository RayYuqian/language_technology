## Chomsky Hierarchy of Formal languages

#### Definitions

##### Language

- A set of sentences that can be created using a limited set of symbols or characters. 
  - E.g., the English language uses the alphabet of 26 letters to create words and sentences.

##### Grammar

- A set of rules that determine which sentences can be constructed using the symbols of the language.
  - It can be regarded as a function whose range is the set of all possible sentences it can generate.

- A grammar of language L can be regarded as a function whose range is exactly L

---

#### Formal Grammar

A **formal grammar** is a quad-tuple G = (Φ,Σ,R,S) where

- Φ is a finite set of symbols called non-terminals. 
  - They can be replaced by other symbols in the grammar rules.
- Σ is a finite set of symbols called terminals. 
  - They cannot be replaced by other symbols in the grammar rules.
- R is a finite set of rules, also called productions.
  - Each rule has the form α → β, where α and β are strings made up of symbols from Φ and Σ. 
  - `α ≠ ε and α ∉ Σ*`
    - The symbol α cannot be empty and cannot consist entirely of symbols from Σ.
- S is a symbol from Φ called the start symbol. 