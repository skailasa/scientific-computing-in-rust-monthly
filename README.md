# Scientific Computing in Rust Monthly

Scientific Computing in Rust Monthly is a monthly newsletter containing the latest information
about scientific computing in the Rust programming language. The newsletter can be viewed online
at [scientificcomputing.rs/monthly](https://scientificcomputing.rs/monthly) or you can sign up
to receive an email copy at [mailinglist.scientificcomputing.rs](https://mailinglist.scientificcomputing.rs).

Items can be added to the newsletter by opening a pull request to this repo. You can find more
information about adding items [below](#contributing-an-item).

## Releasing an issue
Each month, one of the editors of Scientific Computing in Rust Monthly will finialise and release
the month's newsletter. Once the finalisation is complete, this can be done by triggering
the [release newsletter](https://github.com/rust-scicomp/scientific-computing-in-rust-monthly/actions/workflows/release.yml)
workflow.

Before releasing a month's newsletter, the editor should check that everything on the
[editors' checklist](EDITORS_CHECKLIST.md) has been done.

## Contributing an item
To add an item to the next issue of the newsletter, you should
[fork this repository](https://github.com/rust-scicomp/scientific-computing-in-rust-monthly/fork),
edit in your fork, then open a pull request to add your item to the main branch.

The draft for the next newsletter is in the [drafts/](drafts) directory with the filename format
`YYYY-MM.md`. You should edit this file to add your item. Items into the newsletter are sorted into
a the following sections:

* New releases
* Events
* Jobs

You should add your item to the relevant section, or the "Miscellaneous" section if it doesn't fit
any other section.

Items should be written using standard [markdown](https://www.markdownguide.org/cheat-sheet/).
Any text contained between `<!--` and `-->` is a comment and will not be displayed in the final
newsletter.
