# Ruby Client for Google Container Engine API ([Alpha](https://github.com/GoogleCloudPlatform/google-cloud-ruby#versioning))

[Google Container Engine API][Product Documentation]:
The Google Kubernetes Engine API is used for building and managing container
based applications, powered by the open source Kubernetes technology.
- [Client Library Documentation][]
- [Product Documentation][]

## Quick Start
In order to use this library, you first need to go through the following
steps:

1. [Select or create a Cloud Platform project.](https://console.cloud.google.com/project)
2. [Enable billing for your project.](https://cloud.google.com/billing/docs/how-to/modify-project#enable_billing_for_a_project)
3. [Enable the Google Container Engine API.](https://console.cloud.google.com/apis/api/container)
4. [Setup Authentication.](https://googlecloudplatform.github.io/google-cloud-ruby/#/docs/google-cloud/master/guides/authentication)

### Installation
```
$ gem install google-cloud-container
```

### Preview
#### ClusterManagerClient
```rb
require "google/cloud/container"

cluster_manager_client = Google::Cloud::Container.new
project_id_2 = project_id
zone = "us-central1-a"
response = cluster_manager_client.list_clusters(project_id_2, zone)
```

### Next Steps
- Read the [Client Library Documentation][] for Google Container Engine API
  to see other available methods on the client.
- Read the [Google Container Engine API Product documentation][Product Documentation]
  to learn more about the product and see How-to Guides.
- View this [repository's main README](https://github.com/GoogleCloudPlatform/google-cloud-ruby/blob/master/README.md)
  to see the full list of Cloud APIs that we cover.

[Client Library Documentation]: https://googlecloudplatform.github.io/google-cloud-ruby/#/docs/google-cloud-container/latest/google/container/v1
[Product Documentation]: https://cloud.google.com/container-engine
