provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "fhalearslnn/docker-instance/aws"
    key_name = "firstkey"
}
