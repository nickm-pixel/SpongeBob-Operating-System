Inspired from https://www.youtube.com/watch?v=FkrpUaGThTQ

For Linux or MacOS:

> docker run --rm -it -v $(pwd):/root/env myos-buildenv
> For Windows (CMD):
> docker run --rm -it -v "%cd%":/root/env myos-buildenv

Then in the docker container, run

> make build-x86_64
