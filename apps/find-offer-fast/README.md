# Find Offer Fast

The application runs on general-1. Its only deployment source is `apps/find-offer-fast` in https://github.com/anomaly51/general-1-argocd.

API: https://find-offer-fast.api-api-api.com

This cleanup is intentionally prepared for review: before enabling pruning on a retired cluster, recover or back up its old database volumes and remove cascading deletion finalizers from the former Argo CD application. No database migration or data deletion is performed by this pull request.
