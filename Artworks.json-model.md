# Artworks.json

## Add Column

## Add Node/Literal

## PyTransforms
#### _title_uri_
From column: _Title_
``` python
return getValue("ObjectID")+"/title/"
```

#### _artist_uri_
From column: _ConstituentID_
``` python
return  getValue("ObjectID")+"/artist/"
```

#### _provider_uri_
From column: _CreditLine_
``` python
return getValue("ObjectID")+"/provider/"

```


## Selections

## Semantic Types
| Column | Property | Class |
|  ----- | -------- | ----- |
| _Classification_ | `dc:type` | `edm:ProvidedCHO1`|
| _CreditLine_ | `skos:prefLabel` | `edm:Agent2`|
| _Date_ | `dc:date` | `edm:ProvidedCHO1`|
| _Medium_ | `dct:medium` | `edm:ProvidedCHO1`|
| _ObjectID_ | `dc:identifier` | `edm:ProvidedCHO1`|
| _ThumbnailURL_ | `uri` | `edm:WebResource1`|
| _Title_ | `dct:title` | `edm:ProvidedCHO1`|
| _Title_ | `dc:title` | `edm:ProvidedCHO1`|
| _URL_ | `uri` | `edm:ProvidedCHO1`|
| _artist_uri_ | `uri` | `edm:Agent1`|
| _provider_uri_ | `uri` | `edm:Agent2`|
| _values_ | `skos:prefLabel` | `edm:Agent1`|
| _values_ | `edm:begin` | `edm:Agent1`|
| _values_ | `edm:end` | `edm:Agent1`|


## Links
| From | Property | To |
|  --- | -------- | ---|
| `edm:ProvidedCHO1` | `dc:creator` | `edm:Agent1`|
| `edm:ProvidedCHO1` | `edm:provider` | `edm:Agent2`|
| `edm:ProvidedCHO1` | `edm:hasView` | `edm:WebResource1`|
