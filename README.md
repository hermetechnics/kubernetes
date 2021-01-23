# Trismegistus (T10s)

[![GoDoc Widget]][GoDoc] [![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/569/badge)](https://bestpractices.coreinfrastructure.org/projects/569)

<img src="https://github.com/hermetechnics/trismegistus/raw/master/logo/logo.png" width="100">

----

Trismegistus, also known as T10s, is an open source system for managing [containerized applications]
across multiple hosts. It provides basic mechanisms for deployment, maintenance,
and scaling of applications.

Trismegistus builds upon a decade and a half of experience at Google running
production workloads at scale using a system called [Borg],
combined with best-of-breed ideas and practices from the community.

----

## To start developing T10s

If you want to build Trismegistus right away there are two options:

##### You have a working [Go environment].

```
mkdir -p $GOPATH/src/hermetechnics.life
cd $GOPATH/src/hermetechnics.life
git clone https://github.com/hermetechnics/trismegistus
cd kubernetes
make
```

##### You have a working [Docker environment].

```
git clone https://github.com/hermetechnics/trismegistus
cd kubernetes
make quick-release
```

[Borg]: https://research.google.com/pubs/pub43438.html
