---
swagger: "2.0"
x-collection-name: Rotten Tomatoes
x-complete: 1
info:
  title: Rotten Tomatoes
  description: test-our-api-services-using-io-docs-
  contact:
    name: Mike Ralphson
    url: https://github.com/mermade/mashery2openapi
    email: mike.ralphson@gmail.com
  version: "1.0"
host: api.rottentomatoes.com
basePath: /api/public/v1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /lists/movies/opening.json:
    get:
      summary: Get Lists Movies Opening
      description: Get lists movies opening.json.
      operationId: getListsMoviesOpening.json
      x-api-path-slug: listsmoviesopening-json-get
      parameters:
      - in: query
        name: country
        description: Provides localized data for the selected country (ISO 3166-1
          alpha-2) if available
      - in: query
        name: limit
        description: Limits the number of opening movies returned
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Movies
      - Opening
---