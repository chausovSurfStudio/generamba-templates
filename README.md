# generamba-templates

This repository contains a list of [Generamba](https://github.com/rambler-digital-solutions/Generamba) templates.

The detailed information about a template structure is available in [Generamba Wiki](https://github.com/rambler-digital-solutions/Generamba/wiki/Template-Structure).

## Requirements

[Generamba](https://github.com/rambler-digital-solutions/Generamba) 1.3.0 or later.

## List of templates

* [Surf MVP module](https://github.com/surfstudio/generamba-templates/tree/master/surf_mvp_module) - generates a new module of **Surf MVP** architecture

* [Surf MVP Coordinatable module](https://github.com/surfstudio/generamba-templates/tree/master/surf_mvp_coordinatable_module) - generates a new module of architecture **Surf MVP** with routing using Coordinators.

* [Surf MVP Coordinatable Alert module](https://github.com/surfstudio/generamba-templates/tree/master/surf_mvp_coordinatable_alert) - generates a new alert module of architecture **Surf MVP** with routing using Coordinators.

## Installation

To install a template just put these strings in your `Rambafile` and run `generamba template install` in Terminal

```
### Catalogs
catalogs:
- 'https://github.com/surfstudio/generamba-templates'

### Templates
templates:
- {name: needed_template_name}
```
