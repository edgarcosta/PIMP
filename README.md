# CHIMP: Chimp Hopefully Installs Magma Packages

- Can keep up with all the Magma packages on your system?
- and their dependencies?
- Tired of having of managing them one by one?

Then look no further, CHIMP will manage all your Magma packages for you.

# Installing


```
git clone --recurse-submodules -j8 git@github.com:edgarcosta/CHIMP.git
```
or
```
git clone --recurse-submodules -j8 https://github.com/edgarcosta/CHIMP.git
```

and you only need to attach the `CHIMP.spec`


# Updating

You can fetch the most recent version of all packages by doing:
```
git submodule update --remote --jobs=10
```
and consider doing a pull request afterwards.
