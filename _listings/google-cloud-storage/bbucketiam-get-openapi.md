---
swagger: "2.0"
x-collection-name: Google Cloud Storage
x-complete: 0
info:
  title: Google Cloud Storage Get Bucket IAM
  version: 1.0.0
  description: Returns an IAM policy for the specified bucket.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /b/{bucket}/iam:
    get:
      summary: Get Bucket IAM
      description: Returns an IAM policy for the specified bucket.
      operationId: storage.buckets.getIamPolicy
      x-api-path-slug: bbucketiam-get
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      responses:
        200:
          description: OK
      tags:
      - Bucket IAM
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