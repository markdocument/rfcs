# RFCs
This repository has the RFCs for Markdowndocs.

The list of all of them is in the `/rfc` folder.

## Creating an RFC
First, [fork the repository](https://github.com/markdocuments/rfcs/fork).

Then, after that point, create a new file with the following filename format: `0000-your-rfc-name.md`.

Format explained:

- `0000` is the RFC ID
- `your-rfc-name` is the name of your RFC

Fill in `0000` with the next, available ID (should be the exact number after the most recently added ID).

Fill in `your-rfc-name` with the name of your RFC. You should use dashes (`-`) to separate words. Do not use capitals (not even for abbreviations such as `RFC`, that should be `rfc`).

Write a clear title (in title case) and description.

Then, send a pull request with a clear title and description.

## Comment
When they are accepted to receive comments, they will be merged, and to comment, comment on the merged PR.

## When RFCs get closed
When we close an RFC, we will add a statement saying that it has been closed and no new comments will be accepted (we will lock the PR).
