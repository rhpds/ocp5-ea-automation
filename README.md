# OCP5 Early Access Automation

Ansible collection for provisioning the OpenShift 5 Early Access hosted environment
on the Red Hat Demo Platform (RHDP).

## Role: ocp5_ea

Installs OpenShift GitOps, deploys an app-of-apps ArgoCD Application pointing
to the [ocp5-ea-gitops](https://github.com/rhpds/ocp5-ea-gitops) Helm chart repo,
and publishes user data for Showroom.

### Usage

Set `ACTION: provision` to deploy or `ACTION: destroy` to tear down.

See `roles/ocp5_ea/defaults/main.yml` for all configurable variables.
