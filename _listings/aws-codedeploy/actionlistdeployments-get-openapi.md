---
swagger: "2.0"
x-collection-name: AWS CodeDeploy
x-complete: 0
info:
  title: AWS CodeDeploy API List Deployments
  version: 1.0.0
  description: |-
    Lists the deployments in a deployment group for an application registered with the
                applicable IAM user or AWS account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListApplications:
    get:
      summary: List Applications
      description: |-
        Lists the applications registered with the applicable IAM user or AWS
                    account.
      operationId: listApplications
      x-api-path-slug: actionlistapplications-get
      parameters:
      - in: query
        name: nextToken
        description: An identifier returned from the previous list applications call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=ListDeploymentConfigs:
    get:
      summary: List Deployment Configs
      description: |-
        Lists the deployment configurations with the applicable IAM user or AWS
                    account.
      operationId: listDeploymentConfigs
      x-api-path-slug: actionlistdeploymentconfigs-get
      parameters:
      - in: query
        name: nextToken
        description: An identifier returned from the previous list deployment configurations
          call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployments
  /?Action=ListDeploymentGroups:
    get:
      summary: List Deployment Groups
      description: |-
        Lists the deployment groups for an application registered with the applicable IAM
                    user or AWS account.
      operationId: listDeploymentGroups
      x-api-path-slug: actionlistdeploymentgroups-get
      parameters:
      - in: query
        name: applicationName
        description: The name of an AWS CodeDeploy application associated with the
          applicable IAM user            or AWS account
        type: string
      - in: query
        name: nextToken
        description: An identifier returned from the previous list deployment groups
          call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployment Groups
  /?Action=ListDeploymentInstances:
    get:
      summary: List Deployment Instances
      description: |-
        Lists the instance for a deployment associated with the applicable IAM user or AWS
                    account.
      operationId: listDeploymentInstances
      x-api-path-slug: actionlistdeploymentinstances-get
      parameters:
      - in: query
        name: deploymentId
        description: The unique ID of a deployment
        type: string
      - in: query
        name: instanceStatusFilter
        description: 'A subset of instances to list by status:'
        type: string
      - in: query
        name: nextToken
        description: An identifier returned from the previous list deployment instances
          call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployment Instances
  /?Action=ListDeployments:
    get:
      summary: List Deployments
      description: |-
        Lists the deployments in a deployment group for an application registered with the
                    applicable IAM user or AWS account.
      operationId: listDeployments
      x-api-path-slug: actionlistdeployments-get
      parameters:
      - in: query
        name: applicationName
        description: The name of an AWS CodeDeploy application associated with the
          applicable IAM user            or AWS account
        type: string
      - in: query
        name: createTimeRange
        description: A time range (start and end) for returning a subset of the list
          of            deployments
        type: string
      - in: query
        name: deploymentGroupName
        description: The name of an existing deployment group for the specified application
        type: string
      - in: query
        name: includeOnlyStatuses
        description: 'A subset of deployments to list by status:'
        type: string
      - in: query
        name: nextToken
        description: An identifier returned from the previous list deployments call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployments
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