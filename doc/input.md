# CSV

- only comma-separated
- header row
- whitespaces become part of field, clean before if unwanted
- quotes can be used, they don't need be removed, but are of little use at the moment.

- UTF8 capable (e.g. can read chinese names). If you use different encodings, expect strange chars in graph.

- It is highly reccommended that you create small versions of datasets and try them and check manually.
- Also identify possible issues (e.g. use of foreing characters) and find them in the output graph.
  (the original id field stored as attribute as __id)

- do commas in quotes get read???

- One file per entity! If multiple files is the user responsibility to ensure IDs are unique.

- one class must come from a single file, but a single file can include more objects
  (although this representation is unlikely in DB normal form)
