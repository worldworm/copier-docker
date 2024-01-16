<h1 align="center">📋 copier-docker</h1>
<p align="center">
  <i><a href="https://github.com/copier-org/copier">Copier</a> template for <a href="https://github.com/moby/moby">docker</a> projects.</i>
</p>


<!-- Place https://shields.io/ badges here -->
[![GitHub repo stars](https://img.shields.io/github/stars/worldworm/copier-docker)](https://github.com/worldworm/copier-docker)
[![License](https://img.shields.io/badge/license-MIT-green?logo=opensourceinitiative&logoColor=fff)](https://github.com/worldworm/copier-docker/blob/main/LICENSE)
[![GitHub last commit (main)](https://img.shields.io/github/last-commit/worldworm/copier-docker/main)](https://github.com/worldworm/copier-docker/commits/main/)
[![GitHub release](https://img.shields.io/github/v/release/worldworm/copier-docker)](https://github.com/worldworm/copier-docker/releases/latest)
[![GitHub commits since latest release](https://img.shields.io/github/commits-since/worldworm/copier-docker/latest/main)](https://github.com/worldworm/copier-docker/releases/latest)
[![Copier supported version](https://img.shields.io/badge/Copier-v9-blue)](https://github.com/copier-org/copier)



## Features
- precreated Dockerfile
- opencontainers labels
- python and node-frontend presets
- docker-compose.yml support


## Requirements
First install copier:<br>
([from the official installation documentation](https://copier.readthedocs.io/en/stable/#installation))
```bash
pip install copier
```


## Usage



Make sure the requirements are met, then:
```bash
copier copy "https://github.com/worldworm/copier-docker.git" .
```

### Update
To update a template after creating a project, run:
```bash
copier update -a .project/.copier-answers.docker.yml .
```


## Explore more Copier templates
In addition to this template, there are a number of other Copier templates available. For an overview of all available templates, visit the [Templates Showcase repository](https://github.com/worldworm/copier-showcase).

---
<p align="center">
  <i>© <a href="https://github.com/worldworm">worldworm</a> 2024</i>
  <br><i>Licensed under <a href="https://github.com/worldworm/copier-docker/blob/main/LICENSE">MIT</a></i>
</p>
