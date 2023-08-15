This repo contains the Git config for a Ghost blog named ${{ values.name }}

Changes made here can be picked up by Argo CD, ever watching for updates to deploy. Keep the `ghost.marker` file in place with that exact name to keep this repo actively linked to Argo, or rename that file to temporarily break the connection.

To use Ghost in general see the documentation at https://ghost.org/docs/
