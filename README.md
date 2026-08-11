# Procera

**Model development and simulation software for activated sludge processes**

Procera is a configurable model-development, simulation, and analysis environment for activated sludge processes. It combines a visual treatment-process topology with template-defined components, aggregates, parameters, processes, rate expressions, mappings, and Gujer-matrix relationships.

Procera is intended primarily for undergraduate and graduate education, model development, and non-commercial academic investigation. The signed educational templates supplied with the installer support a progressive sequence from introductory substrate–biomass modeling to carbon, nitrogen, and phosphorus removal.

## Download

Download the current installer, user manual, release notes, EULA, and SHA-256 checksums from the [Releases](../../releases/latest) page.

Install Procera using:

`Procera_<version>_x64.msi`

Do not use the automatically generated GitHub source-code archives as the installer.

## Included Software

The public installer contains:

- Procera
- Procera Template Editor
- the bundled Verification Report add-in
- four signed educational templates
- the Quick Start example project

## Included Educational Templates

- Introductory S–X Model
- Introductory C Removal
- Introductory CN Removal
- Introductory CNP Removal

## System Requirements

- 64-bit Windows 10 or Windows 11
- 64-bit processor
- minimum 4 GB RAM
- minimum display resolution of 1600 × 900 pixels

The installer is self-contained. A separate .NET installation is not required.

## License and Permitted Use

Procera is distributed as binary-only freeware for non-commercial educational and academic use.

The application source code is not included, and Procera is not open-source software. Commercial use, redistribution, repackaging, modification, and reverse engineering are subject to the restrictions stated in the applicable EULA.

Installation and use are governed by the EULA supplied with each release.

## Companion Applications

### Procera Plant Designer

Procera Plant Designer is a separately installed companion application for treatment-process design and Procera project generation.

It requires Procera 1.0.1 or later and is not included in the main Procera installer.

Additional information is available in the `Companion Applications/Procera Plant Designer` directory.

## Course Materials

Educational materials developed for use with Procera will be made available in the `Course Materials` directory.

The initial collection will cover activated sludge processes.

## Documentation

Each release includes a version-specific Procera User Manual in PDF format.

Users should retain the exact Procera version, template version, PCM files, and analysis settings used in teaching or research work.

## Bug Reports and Feature Requests

Reproducible software problems and suggestions may be submitted through [GitHub Issues](../../issues).

A bug report should include:

- the exact Procera version;
- the affected application or module;
- the Windows version;
- the template and general project configuration;
- exact reproduction steps;
- expected behavior;
- observed behavior; and
- screenshots or error messages where available.

Remove confidential, personal, institution-restricted, and plant-specific information before uploading files or screenshots.

The issue tracker is not intended for project preparation, model calibration, result interpretation, or individual technical support.

Submission does not guarantee an individual response, workaround, correction, update, or release date.

## Scientific Limitations

Procera results depend on the selected model, template, assumptions, input data, parameter values, topology, operating conditions, and numerical settings.

Procera must not be used as the sole basis for treatment-plant design, construction, equipment selection, regulatory compliance, operational control, environmental protection, safety-related decisions, financial commitments, or other consequential actions.

Users remain responsible for reviewing inputs and outputs and independently verifying important results.

## Releases

All public Procera versions are published through this repository.

The release naming convention is:

- Git tag: `v1.0.0`, `v1.0.1`, `v1.1.0`, and so forth
- Release title: `Procera 1.0.0`, `Procera 1.0.1`, `Procera 1.1.0`, and so forth
- Installer: `Procera_<version>_x64.msi`

Older releases remain available for reproducibility and compatibility review.

## Important Notice About GitHub Archives

GitHub automatically displays `Source code (zip)` and `Source code (tar.gz)` files for each release.

These archives contain only the public files committed to this repository. They do not contain the Procera application source code and must not be used as the Procera installer.
