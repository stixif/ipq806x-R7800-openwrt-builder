# ipq806x-openwrt-builder
Automated builds of IPQ806x OpenWRT repository using GitHub Actions

- robimarko's fork is pulled daily and if last commit is less than a day old a new build is triggered.
- Manual build can also be triggered.
- Build artifacts are stored as releases.
- Build options are embedded in [ipq806x.yaml](/.github/workflows/ipq806x.yaml) file.
