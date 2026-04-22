<div align="center">
    <img src="./brim_logo.png" width="200"/>
    <h1>Brillouin Imaging</h1>
    <h3><em>An ecosystem for storing, sharing and analyzing Brillouin data.</em></h3>
</div>

This organization collects the open-source repositories that make up the **brim ecosystem** — a standardized framework for storing, sharing, and analyzing data from Brillouin light scattering (BLS) microscopy.

> **Reference publication:** Bevilacqua, Hambura, Bouvet et al., *"A standardized file format and open-source analysis framework for Brillouin microscopy data"* · [arXiv:2509.07566](https://arxiv.org/abs/2509.07566)

---

## Why brim?

Brillouin microscopy enables label-free, non-contact 3D mapping of the viscoelastic properties of living cells and tissues. As the field grows, the lack of standardized methods for storing and analyzing spectral data has become a critical bottleneck — limiting reproducibility and making cross-lab comparisons difficult.

The brim ecosystem addresses this by providing:

- A **standardized file format** (`brim`) based on [Zarr v3](https://zarr.dev/), designed for cloud-compatible, hierarchical storage of spectral data, derived maps, and rich acquisition metadata.
- **Open-source tools** for reading, writing, validating, visualizing, and analyzing brim files.

Together, these tools promote [FAIR data practices](https://doi.org/10.1038/sdata.2016.18) (Findable, Accessible, Interoperable, Reusable) across the Brillouin microscopy community.

---

## Repositories

| Repository | Description |
|---|---|
| [Brillouin-standard-file](https://github.com/brillouin-imaging/Brillouin-standard-file) | Specification and discussion of the `brim` file format standard |
| [brimfile](https://github.com/brillouin-imaging/brimfile) | Python library to read and write `brim` files, including spectral data, derived maps, and metadata |
| [BrimView](https://github.com/brillouin-imaging/BrimView) | Browser-based GUI for visualization and real-time spectral analysis of `brim` files — no installation required |
| [brillouin-imaging-napari](https://github.com/brillouin-imaging/brillouin-imaging-napari) | Napari plugin for opening and exploring `brim` files within the napari image viewer |
| [brillouin-imaging-fiji](https://github.com/brillouin-imaging/brillouin-imaging-fiji) | ImageJ/Fiji plugin for opening `brim` files directly in ImageJ |

---

## Getting started

- **View and analyze data** in the browser: [biobrillouin.org/brimview](https://biobrillouin.org/brimview/)
- **Read/write .brim files**: [prevedel-lab.github.io/brimfile](https://prevedel-lab.github.io/brimfile/)
- **Validate a brim file** online (no installation needed): [biobrillouin.org/brim-validator](https://biobrillouin.org/brim-validator/)

---

## Contributing

We welcome contributions, feedback, and extensions from the wider microscopy and bioimaging community. The file format specification is open for discussion — please open an issue in [Brillouin-standard-file](https://github.com/brillouin-imaging/Brillouin-standard-file/issues) to propose changes or raise questions. For bugs and feature requests in individual tools, open an issue in the relevant repository.
For general discussion about the brim ecosystem, you can start a discussion in the [Brillouin imaging organization](https://github.com/orgs/brillouin-imaging/discussions).

We also encourage commercial Brillouin microscope manufacturers to adopt and contribute to this open standard.