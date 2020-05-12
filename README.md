This repo provides RPM packaging for
[facebook/watchman](https://github.com/facebook/watchman). This repo is used to
build the
[breeffy/watchman](https://copr.fedorainfracloud.org/coprs/breeffy/watchman/)
Fedora COPR repository, which you can use to get pre-built RPMs.

To install watchman using Breeffy's COPR repository:

```bash
# Enable the eklitzke/watchman copr repository.
$ sudo dnf copr enable breeffy/watchman

# Install the watchman RPM.
$ sudo dnf install watchman
```


# Supported OS
| Distribution | Version | Architecture |
| ------------ | ------- | ------------ |
| Fedora | 32 | x86_64 |
