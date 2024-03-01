<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-instance-group/blob/master/vendor/modules/instance-group/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraform Google Managed Instance Group Module

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

Simple example with [google_compute_instance_group](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/compute_instance_group)

## Add to Terrafile

```ruby
mod "instance-group", source: "boltops-tools/terraform-google-instance-group"
```

## Import Example

    terraspace bundle example instance-group mig

## Deploy

    terraspace up mig

## Clean Up

    terraspace down mig
