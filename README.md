# gcloud-Overlay
Gentoo Overlay for Google cloud SDK

For details aboug gcloud, visit https://cloud.google.com/sdk/

## Installation
To install the overlay, input:
```bash
layman -o  -f -a google-cloud-sdk
```

You can emerge the file with:
```bash
emerge -a google_appengine
```

Then update your path environment with:
```bash
env-update && source /etc/profile
```