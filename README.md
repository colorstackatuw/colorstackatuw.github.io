# colorstack.cs.wisc.edu

[![LinkedIn](https://img.shields.io/badge/ColorStack%20at%20UW--Madison-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/company/colorstack-at-uw-madison)
[![Instagram](https://img.shields.io/badge/colorstackatuw-E4405F?style=for-the-badge&logo=instagram&logoColor=white&style=flat-square)](https://instagram.com/colorstackatuw)

This repository contains the source files for the ColorStack at UW-Madison website, hosted at [colorstack.cs.wisc.edu](https://colorstack.cs.wisc.edu/).

## Editing The Site

To make changes to the website, place your files in the `public` folder within this Git repository.

> [!WARNING]
> Do not remove `index.html` or `error.html`, as they are required by the CDN.

## Deployment

Once changes are pushed to the repository:

- The changes automatically propagate to the live website.
- The CDN distribution may take between 1 and 5 minutes to redeploy. Please wait for this duration to see your changes live.

## Notes

- This site is hosted under a free tier with a quota of 5 GB. If additional resources are required, please contact the hosting team.
- While HTTP/HTTPS access is open worldwide, SSH access requires a campus IP or WiscVPN connection.
- The default root object for the root and subfolders is `index.html`.
- The custom error document (e.g., for 404 errors) is named `error.html` and located at the root directory. Please customize this file as needed.
