# The Jenkins X Files - Helm Charts

This repository contains the pre-packaged [Helm](https://helm.sh/) charts of the [The Jenkins X Files](https://the-jenkins-x-files.github.io/) - the [Jenkins X](https://jenkins-x.io/) workshop:

- [Mulder](https://github.com/the-jenkins-x-files/mulder) - the Backend API
- [Scully](https://github.com/the-jenkins-x-files/scully) - the Frontend UI

To use this repository, run the following commands:

```
$ helm repo add the-jenkins-x-files https://the-jenkins-x-files.github.io/charts
$ helm repo update
$ helm search mulder
$ helm inspect the-jenkins-x-files/mulder
$ helm search scully
$ helm inspect the-jenkins-x-files/scully
```
