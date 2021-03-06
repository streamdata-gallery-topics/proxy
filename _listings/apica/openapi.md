swagger: "2.0"
x-collection-name: Apica
x-complete: 1
info:
  title: Scenarios API
  version: 1.0.0
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
  '/checks/proxysniffer/{checkId} ':
    ' put ':
      summary: Checks Proxy Sniffer
      description: Updates a proxy sniffer check.
      operationId: -checks-proxysniffer-checkid-
      x-api-path-slug: checksproxysniffercheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/proxysniffer/locations ':
    ' get ':
      summary: Checks Proxy Sniffer Locations
      description: Gets a list of all locations that are available for ProxySniffer
        checks.
      operationId: -checks-proxysniffer-locations-
      x-api-path-slug: checksproxysnifferlocations-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/proxysniffer/{checkId}/results/{resultId}/urldata?format={format} ':
    ' get ':
      summary: Checks Proxysniffer Results
      description: Gets a file that contains ProxySniffer check result data.
      operationId: -checks-proxysniffer-checkid-results-resultid-urldataformatformat-
      x-api-path-slug: checksproxysniffercheckidresultsresultidurldataformatformat-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/proxysniffer/{checkId}/results/urldata ':
    ' post ':
      summary: Checks Proxy Sniffer Results URLdata
      description: Gets ProxySniffer check results in json format by result ids.
      operationId: -checks-proxysniffer-checkid-results-urldata-
      x-api-path-slug: checksproxysniffercheckidresultsurldata-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/proxysniffer/{checkId}/results/{resultId}/errorlog ':
    ' get ':
      summary: Checks Proxy Sniffer Results Error Log
      description: Gets an error log of the given ProxySniffer check result.
      operationId: -checks-proxysniffer-checkid-results-resultid-errorlog-
      x-api-path-slug: checksproxysniffercheckidresultsresultiderrorlog-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/scenarios/proxysniffer/dictionaries ':
    ' post ':
      summary: Scenarios Proxy Sniffer Dictionaries
      description: Adds Proxy Sniffer scenario custom dictionary.
      operationId: postScenariosProxysnifferDictionaries
      x-api-path-slug: scenariosproxysnifferdictionaries-post
      responses:
        200:
          description: OK
      tags:
      - Scenarios
      - Proxy
      - Sniffer
      - Dictionaries
  '/scenarios/proxysniffer/dictionaries/{dictionary_key} ':
    ' get ':
      summary: Scenarios Proxy Sniffer Dictionaries
      description: Gets a Proxy Sniffer scenario custom dictionary by dictionary key.
        Custom dictionary can contain any data used by Proxy Sniffer scripts which
        needs to be stored separately from scripts.
      operationId: getScenariosProxysnifferDictionariesDictionaryKey
      x-api-path-slug: scenariosproxysnifferdictionariesdictionary-key-get
      responses:
        200:
          description: OK
      tags:
      - Scenarios
      - Proxy
      - Sniffer
      - Dictionaries
    ' put ':
      summary: Scenarios Proxy Sniffer Dictionaries
      description: Updates Proxy Sniffer scenario custom dictionary.
      operationId: putScenariosProxysnifferDictionariesDictionaryKey
      x-api-path-slug: scenariosproxysnifferdictionariesdictionary-key-put
      responses:
        200:
          description: OK
      tags:
      - Scenarios
      - Proxy
      - Sniffer
      - Dictionaries