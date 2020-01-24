---
hide: true
category_id: internal
subcategory_id: internal/markdown
id: internal/markdown/internal-links
type: guide
is_index: false
rank: 0
total_steps: 5
sibling_id: internal/markdown
parent_id: internal/markdown
next_page_id: ''
previous_page_id: ''
---

<!-- does not need translation -->

# Internal links

To link to the right internal guides, references, and endpoints, you can use the
following syntax.

```json
[Get a file by ID](endpoint://get_files_id)
[A file](resource://file)
[Get a file](guide://files/get)
[Box](https://box.com)
```

<H>

[Get a file by ID](endpoint://get_files_id)

[A file](resource://file)

[Get a file](guide://files/get)

[Box](https://box.com)

</H>

<Message>

This technique automatically adds the locale to the path. This ensures links
work correctly when translated to other languages.

</Message>

## Short-hand

Additionally, the syntax can be shortened as follows:

```json
[Get a file by ID](e://get_files_id)
[A file](r://file)
[Get a file](g://files/get)
[Box](https://box.com)
```

<H>

[Get a file by ID](e://get_files_id)

[A file](r://file)

[Get a file](g://files/get)

[Box](https://box.com)

</H>