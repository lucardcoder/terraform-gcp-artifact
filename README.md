# artifact-gcp

module "my-repo" {
  source = "./module"
  artifact-config = {
    repository_id = "my-repository"
    location      = "us-central1"
  }
}
