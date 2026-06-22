# Tilera TILE-Gx Documentation

This repository holds the complete Tilera **Multicore Development Environment 4.3.4**
documentation set for the TILE-Gx processor family.

## Layout

This is a plain static site. `index.html` is the original Tilera documentation portal and
serves as the landing page; point a web server at this directory and it works as is.

| Path                           | Contents                                                                                                                    |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| `index.html`                   | The original Tilera doc portal                                                                                              |
| `INDEX.md`                     | Annotated catalog of all 29 PDFs, grouped by topic                                                                          |
| `pdf/`                         | The PDF manuals                                                                                                             |
| `html/`                        | The interactive HTML reference: full GCC, GDB, binutils, ISA, and hypervisor-arch manuals plus every `tile-*` tool man page |
| `UG500_DocOverview.pdf`        | Tilera's own master documentation index                                                                                     |
| `tilera.css`, `TileraLogo.gif` | Styling for the portal                                                                                                      |

## Highlights

- `pdf/UG401-ISA.pdf` - the full TILE-Gx instruction set
- `pdf/UG130-ArchOverview-TILE-Gx.pdf` and `pdf/UG513-ABI.pdf` - architecture and ABI
- `pdf/UG506-mPIPE-Guide.pdf`, `pdf/UG503-MDE-Gx-TRIO-Guide.pdf`, `pdf/UG507-Gx-MiCA-Guide.pdf` - the mPIPE, TRIO (PCIe), and MiCA (crypto/compress) dataplane engines that made the Gx a line-rate network processor
- `html/gcc/`, `html/gdb/`, `html/binutils.html`, `html/as.html` - the TILE-Gx-specific toolchain docs.

## Provenance

This was recovered from a decommissioned TILEmpower-Gx72 unit, and only contains
vendor documentation.

## Licensing

This is Tilera/EZchip proprietary documentation, mirrored for archival purposes
from a defunct vendor. No license is granted. Current rights holders who want something
removed can open an issue or reach out to me via email.
