# gha-clear-workspace

The `timharris777/gha-clear-workspace` action clears the github workspace for the currently running workflow in github actions. This is designed to be used on self-hosted runners where the project workspace persists between workflow runs. Many times cleaning the workspace is essential to success. That being said, it will also work on github hosted runners.

## Usage

This action can be run on any GitHub hosted runners or self-hosted runners as long as `bash` is available as a shell.

```
steps:
  - uses: chick-fil-a/gha-clear-workspace@v1
```
## Contributing

Check out our [contributing guidelines](CONTRIBUTING.md)

## License

[Apache License 2.0](https://github.com/cfacorp/gha-clear-workspace/blob/master/LICENSE)
