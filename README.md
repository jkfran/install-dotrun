# Install Poetry Action

A Github action for installing and configuring [Dotrun](https://snapcraft.io/dotrun).

The action installs Dotrun, adds executables to the runner system path, and sets relevant Dotrun config settings.

## Usage

If all you need is default Dotrun, simply add this to your workflow:

```yaml
- name: Install Dotrun
  uses: jkfran/install-dotrun@main
```

The action is fully tested for Ubuntu runners.

## Contributing

Contributions are always welcome; submit a PR!
