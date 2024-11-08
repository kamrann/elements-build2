# elements - A C++ library

The `elements` C++ library provides <SUMMARY-OF-FUNCTIONALITY>.


## Usage

To start using `elements` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: elements ^<VERSION>
```

Then import the library in your `buildfile`:

```
import libs = elements%lib{<TARGET>}
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
[bool] config.elements.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
