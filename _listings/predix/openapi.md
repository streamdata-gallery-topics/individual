swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/collections/{collectionName}/features:
    post:
      summary: Insert an individual feature into a collection.
      description: |-
        Insert a new feature into the the named collection. The GeoJSON id is used to identify the feature.
        The GeoJSON id included in the url must match the top level id member of the feature provided.
      operationId: insert-a-new-feature-into-the-the-named-collection-the-geojson-id-is-used-to-identify-the-featurethe
      x-api-path-slug: v1collectionscollectionnamefeatures-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Individual
      - Feature
      - Into
      - Collection