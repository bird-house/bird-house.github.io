| ![](images/birdhouse-ecosphere.svg) |
| :--: |
| **Build your own OGC Web Processing Service for geospatial data analysis.** |

# Welcome to Birdhouse
Birdhouse tools enable you to build your own customised
[OGC](https://www.ogc.org/publications/) compute service in support of web-based geospatial (climate) data analysis.

An OGC compute service has a set of processes with defined input and output parameters. These processes can be executed by a client. For example, a process could run the calclulation of a climate indice or the subsetting of [CMIP](https://wcrp-cmip.org/) climate model data.

Birdhouse offers you:

* A [Cookiecutter template](https://cookiecutter-birdhouse.readthedocs.io/en/latest/) to create your own compute service.
* An [Ansible script](https://ansible-wps-playbook.readthedocs.io/en/latest/index.html) to deploy a full-stack compute service including a Slurm queuing manager.
* A web-based application, [Phoenix](https://pyramid-phoenix.readthedocs.io/en/latest/), and ...
* ... a Python library, [Birdy](https://birdy.readthedocs.io/en/latest/),
  suitable for [Jupyter](https://jupyter.org/) notebooks to interact with WPS compute services.
* An OWS security proxy, [Twitcher](https://twitcher.readthedocs.io/en/latest/),
  to provide access control to OGC compute services.

The current (v1.x, legacy) tools support the OGC [Web Processing Service](https://www.ogc.org/publications/standard/wps/) (XML) standard using the [PyWPS](http://pywps.org/) Python implementation.

The new (>v2) tools support [OGC API – Processes](https://www.ogc.org/publications/standard/ogcapi-processes/) (json, rest-api) using the [pygeoapi](https://pygeoapi.io/) Python implementation.

We already have several compute services for climate data analysis, like [Rook](https://github.com/roocs/rook) and [Finch](https://github.com/bird-house/finch).
