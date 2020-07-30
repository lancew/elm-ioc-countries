# elm-countries

> A searchable [IOC](https://en.wikipedia.org/wiki/ISO_3166-1) based list of country names, codes and emoji flags

This is a fork of https://github.com/supermario/elm-countries to provide IOC country codes.

The library is intended to be used qualified (i.e. `Countries.search`, `Countries.all`).

```elm
> import Countries
> Countries.fromCode "AUS"
Just { name = "Australia", code = "AUS", flag = "🇦🇺" }
    : Maybe.Maybe Countries.Country
```

This library uses the official Olympic recognised countries,as per the original module you may wish to adjust the data as appropriate for your own use case. See https://github.com/supermario/elm-countries for examples of how to do so.


## Example

There's an example with a basic country picker in the `example` directory.

```sh
cd example
elm-reactor
```

**Note** You **must** run `elm-reactor` from within the `example` directory to use the correct package dependencies.
