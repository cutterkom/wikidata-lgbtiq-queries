# wikidata-lgbtiq-queries
A collection of SPAQRL queries


[Items that have any Homosaurus value](https://query.wikidata.org/#SELECT%20DISTINCT%20%3Fitem%20%3FitemLabel%20WHERE%20%7B%0A%20%20SERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22%5BAUTO_LANGUAGE%5D%22.%20%7D%0A%20%20%7B%0A%20%20%20%20SELECT%20DISTINCT%20%3Fitem%20WHERE%20%7B%0A%20%20%20%20%20%20%3Fitem%20p%3AP10192%20%3Fstatement0.%0A%20%20%20%20%20%20%3Fstatement0%20%28ps%3AP10192%29%20_%3AanyValueP10192.%0A%20%20%20%20%7D%0A%20%20%20%20LIMIT%20100%0A%20%20%7D%0A%7D)

