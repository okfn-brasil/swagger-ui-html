# swagger-ui-html

Pure-HTML swagger-ui page, for **[OpenAPI](https://www.openapis.org/) descriptors of the Open Knowledge Brasil's projects**.

Adapted from [swagger-ui/dist](https://github.com/swagger-api/swagger-ui/blob/master/dist/index.html) after [swagger-ui/issues](https://github.com/swagger-api/swagger-ui/issues/3229#issuecomment-311830539) good clues, thanks @tleyden.

## Configurations

At the final `<script>` in [index.htm](index.htm), change the variables `hash_URLs` and `hash_default`.

## Using

Clone `index.htm` and `assets/` colder in a server folder, and use its URL:

* default OpenAPI descriptor (as `hash_default`), example http://api.ok.org.br

* specific, by the project's label (as `hash_URLs`) as hash parameter, example http://api.ok.org.br#petstore
