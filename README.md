# As a service Index

To add a new website:

1. Deploy to Cloud Run
2. Create a new Firebase target: `firebase target:apply hosting blog myapp-blog`
3. Add the new site to `firebase.json`
4. Create a [new site in Firebase Hosting](https://console.firebase.google.com/project/as-a-service-dev/hosting/sites)
5. Add a new domain to the site
6. Update DNS