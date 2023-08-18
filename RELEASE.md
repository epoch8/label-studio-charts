helm repo add bitnami https://charts.bitnami.com/bitnami
helm dependency build

helm package heartex/label-studio
helm push label-studio-1.1.8-rq1.tgz oci://ghcr.io/epoch8/label-studio-charts/label-studio