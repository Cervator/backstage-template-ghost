This repo contains the Git config for a Ghost blog named ${{ values.name }}

Changes made here can be picked up by Argo CD, ever watching for updates to deploy. Keep the `ghost.marker` file in place with that exact name to keep this repo actively linked to Argo, or rename that file to temporarily break the connection (and destroy the blog!)

To use Ghost in general see the documentation at https://ghost.org/docs/

To see your new blog visit https://${{ values.name }}.terasology.io - note that the user system here is separate from your chosen admin user.

To enter the admin section go to https://${{ values.name }}.terasology.io/ghost then use the email + password you supplied during setup.
