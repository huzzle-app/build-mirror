# build-mirror

Unmodified copies of third-party packages that some of our build environments install, kept so those builds stay
reproducible after the upstream source stops publishing a version.

## KiCad 9.0.9 (Ubuntu 24.04, amd64)

Release `kicad-9.0.9-ubuntu24.04.1` holds the binary package exactly as published in the KiCad PPA
(`ppa:kicad/kicad-9.0-releases`), together with its complete Debian source package.

| file | sha256 |
|---|---|
| `kicad_9.0.9~ubuntu24.04.1_amd64.deb` | `b7e6d33867631dc44385067b703b4c39eadede2037a260790b19495fe17e43f0` |
| `kicad_9.0.9~ubuntu24.04.1.dsc` | `7dcaad66b7c35c72fb064dc2caa30609551fb098b225c5b6307b907a3631a970` |
| `kicad_9.0.9~ubuntu24.04.1.tar.xz` | `21cf64490fe94cbdfb5f55dcd8d0a33fe5294bba1673a358ece40c605cefde71` |

- Upstream: https://www.kicad.org/ and https://gitlab.com/kicad/code/kicad
- Original location: https://ppa.launchpadcontent.net/kicad/kicad-9.0-releases/ubuntu/pool/main/k/kicad/
- Licence: KiCad is distributed under the GNU General Public License version 3 or later; the full text is in
  [COPYING](COPYING). The `.dsc` and `.tar.xz` files are the corresponding source of the `.deb`. Nothing here is
  modified.
