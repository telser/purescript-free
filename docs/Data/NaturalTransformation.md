## Module Data.NaturalTransformation

#### `NaturalTransformation`

``` purescript
type NaturalTransformation f g = forall a. f a -> g a
```

A natural transformation

#### `Natural`

``` purescript
type Natural f g = NaturalTransformation f g
```

Alias for `NaturalTransformation`


