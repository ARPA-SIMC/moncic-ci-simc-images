# Monci-CI images for CI/CD at Arpae-SIMC

Configuration files to bootstrap the [Monci-CI](https://github.com/ARPA-SIMC/moncic-ci) images supported by CI/CD at Arpae-SIMC.

## Usage

Copy the configuration files in the images dir and then bootstrap, e.g.

```
$ cp fedora38.yaml $MONCI_IMAGES_DIR/
$ monci bootstrap -I $MONCI_IMAGES_DIR fedora38
```
