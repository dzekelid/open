---
swagger: "2.0"
x-collection-name: MySpace Developers
x-complete: 1
info:
  title: My Space
  description: create-apps-and-games-within-the-myspace-platform--monetize-through-advertising-and-virtual-goods-
  version: 1.0.0
host: api.myspace.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /opensearch/videos:
    get:
      summary: Get Opensearch Veos
      description: Returns search results for videos.
      operationId: opensearch.videos.get
      x-api-path-slug: opensearchvideos-get
      parameters:
      - in: query
        name: count
        description: Number of items to return
      - in: query
        name: culture
        description: The culture context of the search
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: searchTerms
        description: Free form search terms or query words
      - in: query
        name: startPage
        description: Which page to start at for the results
      - in: query
        name: tag
        description: Determine if searching on tags, as opposed to contents
      - in: query
        name: videoMode
        description: Search for specific video types
      responses:
        200:
          description: OK
      tags:
      - Opensearch
      - Videos
  /opensearch/images:
    get:
      summary: Get Opensearch Images
      description: Returns search results for images.
      operationId: opensearch.images.get
      x-api-path-slug: opensearchimages-get
      parameters:
      - in: query
        name: count
        description: Number of items to return
      - in: query
        name: culture
        description: The culture context of the search
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: searchTerms
        description: Free form search terms or query words
      - in: query
        name: sortBy
        description: How to sort the images
      - in: query
        name: sortOrder
        description: Indicates whether to sort ascending or descending
      - in: query
        name: startPage
        description: Which page to start at for the results
      responses:
        200:
          description: OK
      tags:
      - Opensearch
      - Images
  /opensearch/people:
    get:
      summary: Get Opensearch People
      description: Returns search results for people.
      operationId: opensearch.people.get
      x-api-path-slug: opensearchpeople-get
      parameters:
      - in: query
        name: count
        description: Number of items to return
      - in: query
        name: countryCode
        description: Country code to search with
      - in: query
        name: culture
        description: The culture context of the search
      - in: query
        name: distance
        description: Distance away from location to return results
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: gender
        description: The gender to filter on
      - in: query
        name: hasPhoto
        description: Filter for only those who have a photo
      - in: query
        name: latitude
        description: Geographic latitude
      - in: query
        name: location
        description: The location field, such as city, state and/or country
      - in: query
        name: longitude
        description: Geographic longitude
      - in: query
        name: maxAge
        description: Maximum age for returned people
      - in: query
        name: minAge
        description: Minimum age for returned people
      - in: query
        name: searchBy
        description: Which field the search should go through
      - in: query
        name: searchTerms
        description: Free form search terms or query words
      - in: query
        name: startPage
        description: Which page to start at for the results
      responses:
        200:
          description: OK
      tags:
      - Opensearch
      - People
---