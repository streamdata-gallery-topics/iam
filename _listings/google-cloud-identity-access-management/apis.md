---
name: Google Cloud Identity Access Management
x-slug: google-cloud-identity-access-management
description: Google Cloud Identity &amp; Access Management (IAM) lets administrators
  authorize who can take action on specific resources, giving you full control and
  visibility to manage cloud resources centrally. For established enterprises with
  complex organizational structures, hundreds of workgroups and potentially many more
  projects, Cloud IAM provides a unified view into security policy across your entire
  organization, with built-in auditing to ease compliance processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
x-kinRank: "9"
x-alexaRank: "0"
tags: IAM
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-identity-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: Google Identity and Access Management (IAM) - Return IAM Access Control Policy
  x-api-slug: v1resourcegetiampolicy-post
  description: |-
    Returns the IAM access control policy for a
    ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-identity-access-management/v1resourcegetiampolicy-post-openapi.md
- name: Google Identity and Access Management (IAM) - Set IAM Access Control Policy
  x-api-slug: v1resourcesetiampolicy-post
  description: |-
    Sets the IAM access control policy for a
    ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-identity-access-management/v1resourcesetiampolicy-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.functions.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.identity.access.management.stack.network
- type: x-concepts
  url: https://cloud.google.com/iam/docs/concepts
- type: x-documentation
  url: https://cloud.google.com/iam/docs/
- type: x-faq
  url: https://cloud.google.com/iam/docs/faq
- type: x-getting-started
  url: https://cloud.google.com/iam/docs/quickstart
- type: x-guides
  url: https://cloud.google.com/iam/docs/how-to
- type: x-website
  url: https://cloud.google.com/iam/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---