# Harbor

A collection of microservices that create a thin layer of abstraction on top of
orchestration systems. Harbor has two major goals, to increase developer experience and
velocity, and to centralize and sway operational concerns to teams dedicated to solving
these problems.


## The Harbor Ecosystem

Harbor is made up of two main APIs. [ShipIt][shipit] and [Trigger][trigger] both serve as the guts and glory of
the major operations that must take place to deploy applications. The rest of the APIs mentioned are mostly
for ease of use with ShipIt and Trigger.

- [Harbor UI][harbor-ui], a GUI interface that ties all the APIs together.
- [Harbor Compose CLI][harbor-compose], a Docker Compose inspired CLI.
- [Terraform Provider][terraform], a Terraform plugin for managing Harbor resources.
- [HelmIt][helmit], the API that allows simple retrieval of application logs.
- [Customs][customs], the API that allows for public facing CI/CD into an internal firewall setup of Harbor.
- [CatalogIt][catalogit], an API that enables the GUI to show images and versions.


### Ecosystem Graphic

coming soon...


## Demo Video

coming soon...



[shipit]: https://github.com/turnerlabs/shipit-api
[trigger]: https://github.com/turnerlabs/trigger-api
[harbor-ui]: https://github.com/turnerlabs/harbor-ui
[harbor-compose]: https://github.com/turnerlabs/harbor-compose
[helmit]: https://github.com/turnerlabs/helmit-api
[customs]: https://github.com/turnerlabs/customs-api
[catalogit]: https://github.com/turnerlabs/catalogit-api
[terraform]: https://github.com/turnerlabs/terraform-provider-harbor
