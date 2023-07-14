# gcp-cloudbuild-image-pull-demo
Use GCP Cloud Build to pull images from a public repo and store in a private GCP Artifact repo.

Configure a Cloud Build trigger with the following substitutions allowing automatic download of the specified versions to the location specified.

### Substitution variables

| Variable Name | Default Value |
| ------------- | ------------- |
| `_LOCATION`  | us-east4  |
| `_SYSDIG_AGENT_IMAGE_TAG`  | 12.15.0  |

Note: The current Google Project is used for the Google Artifact Repository Project ID value.
