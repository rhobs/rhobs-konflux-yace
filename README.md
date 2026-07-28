# rhobs-konflux-yace

Konflux midstream build for [YACE (Yet Another CloudWatch Exporter)](https://github.com/nerdswords/yet-another-cloudwatch-exporter).

Builds YACE from upstream source on UBI 9 minimal base image, providing SBOM, SLSA attestation, and vulnerability scanning for deployment on ROSA HCP Management Clusters.

## Update submodule

Update the submodule to a new upstream release:
```bash
cd yet-another-cloudwatch-exporter
git fetch --tags
git checkout v0.62.0
cd ..
git add yet-another-cloudwatch-exporter
git commit -m "Update YACE submodule to v0.62.0"
git push
```
