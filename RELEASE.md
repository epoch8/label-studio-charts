cd heartex
helm package label-studio
helm push label-studio-1.1.8-rq0.tgz oci://ghcr.io/epoch8/label-studio-charts/label-studio