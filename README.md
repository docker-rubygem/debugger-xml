[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/debugger-xml.svg)](https://hub.docker.com/r/rubygem/debugger-xml/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/debugger-xml.svg)](https://hub.docker.com/r/rubygem/debugger-xml/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/debugger-xml.svg)](https://hub.docker.com/r/rubygem/debugger-xml/)
[![Gem Downloads](https://img.shields.io/gem/dt/debugger-xml.svg)](https://rubygems.org/gems/debugger-xml/)
# debugger-xml

Auto-Generated Docker image for debugger-xml to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/debugger-xml`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/debugger-xml`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/debugger-xml`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/debugger-xml/)
