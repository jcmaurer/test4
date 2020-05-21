# Queries1
## Queries2
### Query Parameters
All collections should support the following query parameters (if applicable):
_abc
more text_

| GET                | POST | DELETE | PATCH |
|--------------------|------|--------|-------|
| _abcdef | -    | -      | -     |
| more_ | -    | -      | -     |
| abc_def_ | -    | -      | -     |
| abc_def | -    | -      | -     |
| query             | -    | -      | -     |
| ids                | -    | ids    | ids   |
| _italic_              | names | names  | names |
| **bold**              | -    | -      | -     |
| ~~Strikeout~~             | -    | -      | -     |
| sort               | -    | -      | -     |

1: Embedded _italic text_ and this **bold text**

2: Embedded _italic_text_ and this **bold**text**

so the foo-bar relationship will support foo_names, foo_ids, bar_names, and bar_ids as query parameters to uniquely identify a record.

