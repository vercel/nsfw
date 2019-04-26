# nsfw

This is a fork of [Axosoft/nsfw](https://github.com/Axosoft/nsfw), with the only change that it allows passing a custom path for the native node module instead of shipping it with the package itself.

ZEIT uses this system in [Now CLI](https://github.com/zeit/now-cli) for powering the `now dev` command.

## Creating a Release

Whenever you want to publish a new release, simply invoke `release patch -P` (or `major`, `minor` depending on the kind of release). After that, wait for the release to have 4 binaries [here](https://github.com/zeit/nsfw/releases). Once it has, you're done.

---

This project is **not maintained**, other than the fact that it is kept in sync with the original.
