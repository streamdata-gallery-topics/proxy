---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Checks Proxysniffer Checks Proxy Sniffer
  version: 1.0.0
  description: Creates a new ProxySniffer check.
host: api.pingdom.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
basePath: /
paths:
  '/checks/proxysniffer ':
    ' post ':
      summary: Checks Proxy Sniffer
      description: Creates a new ProxySniffer check.
      operationId: -checks-proxysniffer-
      x-api-path-slug: checksproxysniffer-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
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