# gcloud-Overlay
Gentoo Overlay for Google cloud SDK

For details aboug gcloud, visit https://cloud.google.com/sdk/

## Installation
To install the overlay (requires app-portage/layman), input:
```bash
layman -o https://raw.githubusercontent.com/MichaelOVertolli/gcloud-Overlay/master/google-cloud-sdk.xml -f -a google-cloud-sdk
```

You can emerge the file with:
```bash
emerge -a google-cloud-sdk
```

Then update your path environment with:
```bash
env-update && source /etc/profile
```
