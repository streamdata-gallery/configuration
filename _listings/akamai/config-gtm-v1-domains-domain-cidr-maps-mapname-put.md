---
swagger: "2.0"
info:
  title: Akamai Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /config-gtm/v1/domains/{domain}/cidr-maps/{mapName}:
    put:
      summary: Create or Update a CIDR Map
      description: Create or Update a CIDR Map
      operationId: configgtmv1domainsdomaincidrmapsmapname
      parameters:
      - in: String
        name: domain
        description: Name of Traffic Management domain
        type: string
      - in: String
        name: mapName
        description: Name of CIDR Map to create or update
        type: string
      responses:
        200:
          description: OK
      tags:
      - configurations
      - gtm
      - domains
      - cr
      - maps
definitions: []
x-collection-name: Akamai
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