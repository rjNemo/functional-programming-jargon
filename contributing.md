# Contributing

This project is a work in progress. Contributions are very welcome.

## Hard rules

There is a pre-commit hook that runs:  `npm run test && npm run roadmarks` for linting the readme and creating the TOC.

That said, we'd like to maintain some consistency across the document.

## Style guide

1. Every definition should include at least one Go code example.
2. Definitions should be written using the simplest language possible. Every word should tell.
3. Target programmers that have no functional programming experience.
4. We value understandability more than accuracy. e.g. It's okay to describe a functor as a container.
5. Don't overuse jargon even if defined elsewhere in the document.
6. Link to terms defined in the document when you use them in a definition.
7. Avoid big walls of text

## Code conventions

[Go Style Guide](https://github.com/uber-go/guide/blob/master/style.md)

* Be consistent with other examples
* Prefer arrow functions
* Parenthesis around function arguments
* Put output values in comments
* Keep it short and simple

This styleguide is a WIP too! Send PRs :)
