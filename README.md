# dotfiles

Run the `init` script.

See `manifest` for a list of the managed files.

Dotfiles are created as symlinks to the directory containing this repository - so be careful when moving or deleting it.

Shell init supports sourcing `~/.secretsrc` if it exists, so export anything sensitive from there.

## Configuration

Optional environment variables:

- `ENABLE_GOOGLE_CLOUD_SDK`
