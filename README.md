# As a service Index

To add a new website:

1. `SERVICE=<service>`
1. Deploy to Cloud Run
1. Create a new site: `firebase hosting:sites:create $SERVICE-as-a-service`
1. Create a new Firebase target: `firebase target:apply hosting $SERVICE $SERVICE-as-a-service`
1. Add the new site to `firebase.json`
1. Add a new domain to the site
1. Update DNS