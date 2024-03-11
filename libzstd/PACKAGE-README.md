# libzstd - A C library

This is a `build2` package for the [`<UPSTREAM-NAME>`](https://<UPSTREAM-URL>)
C library. It provides <SUMMARY-OF-FUNCTIONALITY>.


## Usage

To start using `libzstd` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: libzstd ^<VERSION>
```

Then import the library in your `buildfile`:

```
import libs = libzstd%lib{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
lib{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.libzstd.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>