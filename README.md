# kfp

The goal of the CFT Kubeflow Pipelines module is to automate the manual steps required to configure and setup a KFP cluster on GCP. The Kubeflow Pipelines module will provision the foundational infrastructure for a long-lived Kubeflow Pipelines cluster on GKE using additional resources, such as Cloud SQL, Cloud Storage, and optionally Cloud IAP. This module will spin up the necessary GCP resources and delegate the installation of KFP to Kustomize.