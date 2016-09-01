# Harbor

A collection of microservices that create a thin layer of abstraction on top of 
orchestration systems. Harbor has two major goals, to increase developer experience and 
velocity, and to centralize and sway operational concerns to teams dedicated to solving 
these problems.

## The Harbor Ecosystem

Harbor is made up of two main apis. [Shipit][shipit] and [Trigger][trigger] both serve as the guts and glory of
the major operations that must take place to deploy applications. The rest of the apis mentioned are mostly
for ease of use with Shipit and Trigger.

- [Harbor UI][harbor-ui] is the GUI interface that ties all the apis together
- [Harbor Compose][harbor-compose] is the docker-compose inspired interface
- [Helmit][helmit] is the api that allows simple retrieval of application logs 
- [Customs][customs] is the api that allows for public facing CI/CD into an internal firewall setup of Harbor

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
