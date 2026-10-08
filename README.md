# codewars-katas-data

JSON data for Codewars kata.

## Data

Each kata is stored as a separate JSON file:

```text
katas/
├── 5a00a8b5ffe75f8888000080.json
├── ...
└── ...
```

Each file contains selected metadata about a Codewars kata:

* ID
* name
* slug
* category
* rank
* languages
* URL
* dates
* author
* approver
* statistics
* tags
* issues and suggestions

## Source

The data is collected from the [Codewars API](https://dev.codewars.com/).

## Organization

Maintained by [CodewarsTools](https://github.com/CodewarsTools).

## Related Projects

* [codewars-api-schemas](https://github.com/CodewarsTools/codewars-api-schemas) — JSON Schemas for Codewars API data.
* [codewars-api-schemas-tests](https://github.com/CodewarsTools/codewars-api-schemas-tests) — tests for the JSON Schemas.
