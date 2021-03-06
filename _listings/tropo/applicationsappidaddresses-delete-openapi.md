---
swagger: "2.0"
x-collection-name: Tropo
x-complete: 0
info:
  title: Tropo Delete Applications Appid Addresses
  description: Delete applications appid addresses.
  version: v1
host: api.tropo.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /applications:
    delete:
      summary: Delete Applications
      description: Delete applications.
      operationId: deleteApplications
      x-api-path-slug: applications-delete
      parameters:
      - in: query
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Applications
    get:
      summary: Get Applications
      description: Get applications.
      operationId: getApplications
      x-api-path-slug: applications-get
      parameters:
      - in: query
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Applications
    post:
      summary: Post Applications
      description: Post applications.
      operationId: postApplications
      x-api-path-slug: applications-post
      parameters:
      - in: query
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Applications
    put:
      summary: Put Applications
      description: Put applications.
      operationId: putApplications
      x-api-path-slug: applications-put
      parameters:
      - in: query
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Applications
  /applications/{AppId}/addresses:
    delete:
      summary: Delete Applications Appid Addresses
      description: Delete applications appid addresses.
      operationId: deleteApplicationsAppAddresses
      x-api-path-slug: applicationsappidaddresses-delete
      parameters:
      - in: path
        name: AppId
      - in: query
        name: applicationId
      responses:
        200:
          description: OK
      tags:
      - Applications
      - AppId
      - Addresses
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---