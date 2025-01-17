### Unreleased

- Add combinators for standard library container types: `ref`, `Lazy.t`,
  `Seq.t`, `Queue.t`, `Stack.t`, `Hashtbl.t`, `Set.t` and `Map.t`.
  (#43, @CraigFe)

- Improve PPX `Repr.t` generation for types in the standard library. References
  to e.g. `Bool.t` or `Stdlib.Int32.t` will be resolved to the corresponding
  combinators. (#43, @CraigFe)

- Add support for deriving mutually-recursive pairs of type representations
  with `ppx_repr`. (#42, @CraigFe)

### 0.2.1 (2021-01-18)

- Support Ppxlib versions >= 0.18.0. (#35, @CraigFe)
- Add missing dependency on `ppx_deriving`. (#36, @CraigFe)
- Add a representation of the `Either.t` type. (#33, @CraigFe)

### 0.2.0 (2020-12-18)

- Improve performance of variable-size integers encoding and decoding.
  (#24, #30, @samoht)
- Require `short_hash` operations to be explicitly unstaged.
  (#15, @CraigFe)
- Require `equal` and `compare` operations to be explicitly unstaged.
  (#16, @samoht)

### 0.1.0 (2020-10-16)

Initial release.
