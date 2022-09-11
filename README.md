# PyCon SK 2022

*This repo contains sources to my talk on PyCon*

## Best practices for building Docker images for Python apps

Docker is very popular among developers and many teams use it to deliver their software. 
I want to use it too, but my images are large and take forever to build. 
Does it have to be like that? Is there a better way to do it?

In this presentation, we will go through the whole process of building 
a docker image for a Python web app. How to select a base image, how to optimize the size, 
and how to increase the speed of build. We will think about security, logging, 
and caching and see how to do it all in CI. You will end up with the set of applicable 
best practices in creating Docker images that you can use in your projects.

**Slides:** 
[Google Slides](https://docs.google.com/presentation/d/1qGdYrrjU7mnuzYLYnlpKmSVjyTqpjumDH0lZa9a7UmQ/) | [Speaker Deck](https://speakerdeck.com/jozo/best-practices-for-building-docker-images-for-python-apps)