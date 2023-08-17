# Public wiki for OurWorld Venture Creator

> see [[...](https://ourworldventures.github.io/info_ourworld)]([...](https://ourworldventures.github.io/info_ourworld/intro/intro.html))

## To Develop 

### Requirements

- Make
- [mdbook](https://rust-lang.github.io/mdBook/guide/installation.html)

### build

`make build`

### Serve

`make serve`

will open the browser  

### Contribute

If you want to contribute, you should follow this steps:

1. Add the md file to [src](./src) directory.
2. Add the path of the md file to [SUMMARY](./src/SUMMARY.md).
3. Then use `make build` and `make serve` to see your changes on the browser.
