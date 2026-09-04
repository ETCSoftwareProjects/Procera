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

Procera Plant Designer is a separately installed companion application for ATV-DVWK-A 131-based activated sludge process design and Procera project generation.

It requires Procera 1.0.1 or later and is not included in the main Procera installer.

- [Procera Plant Designer information](Companion%20Applications/Procera%20Plant%20Designer)
- [Download Procera Plant Designer 0.1.4](../../releases/tag/plant-designer-v0.1.4)

## Course Materials

Procera educational activities provide structured assignments for teaching and learning activated sludge process concepts through modeling and simulation.

Each activity may include an assignment workbook, Procera project or template files, supporting materials, and a short video briefing. Activity ratings and user feedback are also available through the course-materials collection.

- [Browse Procera Course Materials](Course%20Materials)
- [Watch the Procera Educational Activity Series on YouTube](https://www.youtube.com/@ETCSoftwareProjects/playlists)

The YouTube videos are activity briefings rather than solution videos. They introduce the purpose and setup of each activity and demonstrate only the initial steps needed to begin the assignment.

## Documentation

Each release includes a version-specific Procera User Manual in PDF format.

Users should retain the exact Procera version, template version, PCM files, and analysis settings used in teaching or research work.

## Procera User Rating

Users who have used Procera are invited to provide feedback through the common Procera User Feedback survey.

The public rating is based only on the response to:

> **Overall, how would you rate Procera?**

Ratings use a five-point scale. To avoid displaying unstable ratings based on very small numbers of responses, a public rating is shown only after at least **10 responses** have been collected. Other survey responses are not published on this page.

<!-- PROCERA_RATING_START -->
**Not yet rated**  
**Responses:** 0
<!-- PROCERA_RATING_END -->

[Provide Procera User Feedback](https://docs.google.com/forms/d/e/1FAIpQLScPnSf4UaFd5WfNsERoe8g_Zh7tJe5UAivC4EtMrCoFdbBgtQ/viewform?usp=publish-editor)

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
