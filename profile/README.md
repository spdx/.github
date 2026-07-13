# System Package Data Exchange (SPDX)

Main Website: https://spdx.dev/

This organization houses the primary development activity for SPDX. Use the
categories below to find the repositories you are interested in.

## Learning about SPDX SBoM and Examples

These repositories are useful if you are looking for more information about how
to use SPDX and example SPDX files.

 * [using](https://github.com/spdx/using) - This repository contains long-form
   text that explains how to use SPDX, or walks readers through various SPDX
   use cases.
 * [spdx-examples](https://github.com/spdx/spdx-examples) - This repository
   contains example SPDX files covering various versions and use cases

## SPDX SBOM tooling

These repositories contain SPDX related tools, language bindings,
and dependency manager plugins, which are useful
if you want to produce or consume SPDX documents.

### Online tools

 * [spdx-online-tools](https://github.com/spdx/spdx-online-tools) - Source for the [tools.spdx.org](https://tools.spdx.org/app/)
   web application

### Build and dependency management tools

- [spdx-gradle-plugin](https://github.com/spdx/spdx-gradle-plugin) -
  This plugin generates JSON formatted SPDX SBOMs for Gradle projects.
- [spdx-maven-plugin](https://github.com/spdx/spdx-maven-plugin/) -
  A plugin to Maven which produces SPDX documents for artifacts described in
  the Maven POM file.
- [rollup-plugin-spdx](https://github.com/spdx/rollup-plugin-spdx) -
  When added to a Rollup configuration, this plugin will create an SBOM file
  for the package that is being built.
- [yarn-plugin-spdx](https://github.com/spdx/yarn-plugin-spdx) -
  A Yarn plugin to create SBOM files in the SPDX format.

### Language bindings

#### C++

- [spdx-cpp-model](https://github.com/spdx/spdx-cpp-model) - Low level
  C++ library for reading and writing SPDX documents

#### Go

 * [tools-golang](https://github.com/spdx/tools-golang) - Go library for
   dealing with SPDX documents
 * [spdx-go-model](https://github.com/spdx/spdx-go-model) - Low level Go
   library for reading and writing SPDX documents

#### Java

 * [tools-java](https://github.com/spdx/tools-java) - Java command line utility for managing
   and converting SPDX documents
 * [spdx-java-library](https://github.com/spdx/spdx-java-library) - Java library supporting
   reading, writing, converting, and validating SPDX documents
 * spdx-java-* - Support libraries used by the spdx-java-library.
   Descriptions of these repos can be found in the
   [spdx-java-library API documentation](https://github.com/spdx/spdx-java-library?tab=readme-ov-file#api-documentation)

#### JavaScript

 * [tools-ts](https://github.com/spdx/tools-ts) - TypeScript / JavaScript library for writing SPDX documents

#### Python

- [tools-python](https://github.com/spdx/tools-python) - Python library for
  dealing with SPDX documents
- [spdx-python-model](https://github.com/spdx/spdx-python-model) - Low level
  Python library for reading and writing SPDX documents

## SPDX 3 SBoM Model

These repositories define the SPDX 3 SBoM Standard

 * [spdx-3-model](https://github.com/spdx/spdx-3-model) - This is the main SPDX
   3 model files. If you would like to modify or extend the SPDX 3
   specification, start here.
 * [spdx-spec](https://github.com/spdx/spdx-spec) - Source for the canonical SPDX
   specification at [spdx.github.io/spdx-spec/](https://spdx.github.io/spdx-spec/).
   This contains static content like chapters and annexes.
   For the model files, see spdx-3-model.
 * [spec-parser](https://github.com/spdx/spec-parser) - This is the tool that
   translates the SPDX 3 model files from Markdown to various outputs

## SPDX License List

These repositories are related to the SPDX License List

- [license-list-XML](https://github.com/spdx/license-list-XML) -
  The XML Source for the SPDX License List.
- [license-list-data](https://github.com/spdx/license-list-data) -
  The generated content (e.g. Web site, JSON, etc) from the License List XML.
- [licenseListPublisher](https://github.com/spdx/LicenseListPublisher) -
  Source for the tool that generates the license list data.

## SPDX Cryptographic Algorithm List

These repositories are related to the SPDX Cryptographic Algorithm List

- [cryptographic-algorithm-list](https://github.com/spdx/cryptographic-algorithm-list) -
  This repository contains the SPDX Cryptographic Algorithms List,
  a standardized, community-curated list of cryptographic algorithms.

## Community

These repositories are related to the SPDX Community activities

 * [meetings](https://github.com/spdx/meetings) - Information about SPDX
   meetings including schedule, links to join, minutes, etc.
 * [outreach](https://github.com/spdx/outreach) - Outreach resources for SPDX
   (e.g. Conference talks, presentations, etc.)
 * [governance](https://github.com/spdx/governance) - Governance practices for the SPDX Working Group.
 * [GSoC](https://github.com/spdx/GSoC) -
   SPDX participation in Google Summer of Code program.
