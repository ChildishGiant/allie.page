# allie.page

This repo has all the source code to make my website [allie.page](https://allie.page). It's a fork of [al-folio](https://github.com/alshedivat/al-folio) with some customisations.

## Development
If you want to, for some ungodly reason, work on this site you need to

- First, install [docker](https://docs.docker.com/get-docker/) and [docker-compose](https://docs.docker.com/compose/install/).
- Then, clone this repository to your machine:

```bash
$ git clone git@github.com:ChildishGiant/childishgiant.github.io.git allie.page
$ cd allie.page
```

Finally, run the following command that will pull a pre-built image from DockerHub and will run your website.

```bash
$ docker-compose up
```

Now open up your browser and go to [localhost:8080](http://localhost:8080/) and you should see the site.

For more info, have a look at the [original docs for al-folio](https://github.com/alshedivat/al-folio#table-of-contents).
