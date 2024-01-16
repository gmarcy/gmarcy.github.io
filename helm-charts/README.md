## homelab-cert-manager-webhook

This is a helm repository for [homelab-cert-manager-webhook](https://github.com/gmarcy/homelab-cert-manager/tree/main/deploy/homelab-cert-manager-webhook).
See available versions [here](https://github.com/gmarcy/gmarcy.github.io/tree/main/helm-charts)

    # add the repository
    helm repo add homelab-cert-manager-webhook https://gmarcy.github.io/homelab-cert-manager-webhook
    # make sure we're up to date
    helm repo update
    # take a look at any configuration you might want to set
    helm show values homelab-cert-manager-webhook/homelab-cert-manager-webhook
    # install the chart
    helm install --namespace cert-manager homelab-cert-manager-webhook/homelab-cert-manager-webhook

## homelab-letsencrypt-issuers

This is a helm repository for [homelab-letsencrypt-issuers](https://github.com/gmarcy/homelab-cert-manager/tree/main/deploy/homelab-letsencrypt-issuers).
See available versions [here](https://github.com/gmarcy/gmarcy.github.io/tree/main/helm-charts)

    # add the repository
    helm repo add homelab-letsencrypt-issuers https://gmarcy.github.io/homelab-letsencrypt-issuers
    # make sure we're up to date
    helm repo update
    # take a look at any configuration you might want to set
    helm show values homelab-letsencrypt-issuers/homelab-letsencrypt-issuers
    # install the chart
    helm install --namespace cert-manager homelab-letsencrypt-issuers/homelab-letsencrypt-issuers
