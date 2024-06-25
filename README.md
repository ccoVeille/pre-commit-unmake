# pre-commit-unmake

This repository brings [unmake](https://github.com/mcandre/unmake) hook for [pre-commit](https://github.com/pre-commit/pre-commit)

`unmake` is a `Makefile` files linter. It helps to spot errors in these files.

More information on [the project page](https://github.com/mcandre/unmake).

For more detail about pre-commit project on the [official website](https://pre-commit.com/).

## Using this hook

Add this to your `.pre-commit-config.yaml`

```yaml
    - repo: https://github.com/ccoVeille/pre-commit-unmake
      rev: v1.0.0
      hooks:
        - id: unmake
```

Then use

```console
$ pre-commit autoupdate
```

For more information about pre-commit configuration, please refer to the [official documentation](https://pre-commit.com/index.html#pre-commit-configyaml---repos).

## Motivation

`pre-commit` is a great tool.

`unmake` is a great tool.

Let's bring support to `unmake` in `pre-commit`

An [issue](https://github.com/mcandre/unmake/issues/242) and a [PR](https://github.com/mcandre/unmake/pull/244) had requested `unmake` owner to support it.

The owner refused to consider adding pre-commit support… So here, we are 😬 😁,

I created https://github.com/ccoVeille/pre-commit-unmake to provide it
