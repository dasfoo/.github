Files shared across organization repositories.

## `.github`

This directory contains files which are automatically picked up by GitHub and
displayed on various pages of oraganization repositories. Read more about
[Default Community Health Files](https://help.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file).

## `workflows`

Files in this directory are not parsed by GitHub. An `update-overlays.yml` file
is a workflow that, when executed, will copy over an updated version of itself
from this repository, along with any other workflows here. It also downloads
appropriate overlays from the [overlays](https://github.com/dasfoo/overlays)
repository.
