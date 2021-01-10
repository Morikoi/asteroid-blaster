
# Contributing

Thanks for considering to contribute to o11y.love :)

You can fork the project [https://gitlab.com/everyonecancontribute/observability/o11y.love](https://gitlab.com/everyonecancontribute/observability/o11y.love) and send a merge request to review.

## Proposals and Feedback

You can always fork the project and suggest a change in a Merge Request as a draft. 

If you've found a problem, or miss something, you can also open a [new issue in the project](https://gitlab.com/everyonecancontribute/observability/o11y.love/-/issues/new?issuable_template=default) following the template.


## Preview in MkDocs

This project uses MkDocs with the Material theme. In order to render a preview, use the [following options](https://squidfunk.github.io/mkdocs-material/creating-your-site/#previewing-as-you-write).

If you are using a tablet or mobile, we recommend to use [Gitpod](#gitpod) in your browser.

### Gitpod

Open the project or your fork and change the selector from `Web IDE` to `Gitpod`.

Alternatively, use [https://gitpod.io/#https://gitlab.com/everyonecancontribute/observability/o11y.love](https://gitpod.io/#https://gitlab.com/everyonecancontribute/observability/o11y.love)

### Docker

Install Docker and run the container with port-forwarding to localhost:8000. The source directory is mapped into the container.

```
$ docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material`
```

### Local source environment

Install Python 3.9+ and pip, for example with Homebrew on macOS.

```
$ brew install python
```

o11y.love requires MkDocs themes and plugins which are defined in `requirements.txt`. Install them with the following command:

```
$ pip install -r requirements.txt
```

Depending on your environment, the `pip` command is called `pip3`.

You can run MkDocs with the following command:

```
$ mkdocs serve
```

More verbose output for debugging:

```
$ mkdocs serve -v
```


### Static Build

```shell
$ docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material build
```

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Style Guide

### Add items to topics 

For adding tools and projects, follow the existing structure.
