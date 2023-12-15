# Intellij - Java

## Which approach did we choose ?

Intellij has a powerful system of Structural search inspection. It allows you to search for a pattern in your code and to apply a quick fix to it.

## Tutorial to import the configuration file

Here is a video to show you how to install the Poka Yoke for Intellij IDEA :

- You should clone the repository before starting the video

<iframe src="https://drive.google.com/file/d/1iQ62J2gvqjvhcafB-XagguPnAPybyoMJ/preview" width="640" height="480" allow="autoplay"></iframe>

## List of all structural search inspection implemented :

- Avoid using `@MockBean` or `@SpyBean` in a test class
- Avoid using `@DirtyContext` in a test class
- Avoid using primary type in entity with generated ID
- Avoid using primary on a nullable field in an entity [WIP]
