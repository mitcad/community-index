# Mitcad community index

A list of component libraries for [Mitcad](https://github.com/mitcad/Mitcad).
Mitcad's Tools › Libraries › Community Library reads it to find libraries
before they are fetched. The index only lists libraries: each library stays
in its own git repository.

- `mitcad-index.json`: the index itself.
- `libraries/<id>.json`: one entry per library (its URL, licence,
  components and the versions the maintainers reviewed).

To propose a library, write its entry with
`mitcad-cli library index-entry <folder> --url <url>` and open a pull
request that adds it under `libraries/`. Every library needs a licence
(see the format in Mitcad's `docs/libraries.md`).

The index's own files are CC0-1.0.
