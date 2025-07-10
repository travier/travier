# Timothée Ravier (Siosm)

Hi there! 👋 I am a Linux 🐧 system and security engineer interested in safe
programming languages 🦀 and container focused operating systems 📦.

## CoreOS engineering

I am currently a member of the CoreOS team at [Red Hat], working on [Fedora
CoreOS] and [Red Hat Enterprise Linux CoreOS].

CoreOS systems are all about running containers at scale with [Kubernetes]
distributions ([OpenShift], [OKD], [Typhoon]) or on a single server with
[podman] and [quadlet].

[See talks about Fedora CoreOS and CentOS Stream CoreOS](talks.md#fedora-coreos-and-centos-stream-coreos).

## Fedora Atomic Desktops (Silverblue, Kinoite, etc.)

I am a maintainer of the [Fedora Atomic Desktops]. They are container focused
desktop operating systems based on [rpm-ostree], [podman] and [Flatpak]. I
primarily maintain the [Silverblue] and [Kinoite] variants which respectively
feature the [GNOME] and [KDE Plasma] desktops environments.

The [Fedora Atomic Desktops] are also the base for the [Universal Blue] images
([Aurora], [Bazzite], [Bluefin]) that include drivers (NVIDIA), codecs and
other changes that we can not include in Fedora, generally for legal reasons. I
recommend giving them a try if your hardware requires this kind of support.

[See talks about Fedora Atomic Desktops](talks.md#fedora-atomic-desktops-and-flatpaks).

## KDE Apps as Flatpaks

[Fedora Atomic Desktops] systems (Silverblue, Kinoite, etc.) use
[Flatpaks][Flatpak] to make graphical applications easily available to users. I
am part of the team that maintains the [KDE applications] Flatpaks in
[Flathub]. I am also looking at packaging the missing ones and improving the
integration in KDE Invent and KDE development in general.

[See talks about Flatpaks](talks.md#fedora-atomic-desktops-and-flatpaks).

## Toolbox (and distrobox) images

To make it easier to run various popular distributions with [toolbox] or
[distrobox], I have created a community maintained repository to share the
maintenance of container images:
[toolbx-images](https://github.com/toolbx-images/images). See [Community
maintained images for toolbox (and
distrobox)](https://tim.siosm.fr/blog/2022/12/05/toolbx-community-images/) for
more details.

## Systemd system extensions (sysexts)

To be able to safely extend CoreOS and Atomic Desktop systems without resorting
to package layering or derivation, I am working on creating systemd system
extensions (sysexts) for various common use cases. Those sysexts are currently
experimental and unofficial, but should be usable and stable. See the
[fedora-sysexts] repo. I am also working on a more ergonimic user experience
for managing those sysexts with the [sysexts-manager] project.

## Reference pages

- [Talks and podcasts](talks.md)
- [Good reads](goodreads.md)

## How to follow or contact me

- Mastodon: [siosm@floss.social](https://floss.social/@siosm)
- Matrix: [@siosm:matrix.org](https://matrix.to/#/@siosm:matrix.org)

## Accounts on other Git forges

[GitLab.com](https://gitlab.com/Siosm) |
[KDE GitLab](https://invent.kde.org/ravier) |
[GNOME GitLab](https://gitlab.gnome.org/travier) |
[Freedesktop GitLab](https://gitlab.freedesktop.org/travier) |
[Fedora Pagure](https://pagure.io/user/siosm) |
[Fedora Package Sources](https://src.fedoraproject.org/user/siosm)

[Red Hat]: https://www.redhat.com
[Fedora CoreOS]: https://getfedora.org/en/coreos
[Red Hat Enterprise Linux CoreOS]: https://docs.redhat.com/en/documentation/openshift_container_platform/4.18/html/architecture/architecture-rhcos
[Kubernetes]: https://kubernetes.io
[OpenShift]: https://www.openshift.com
[OKD]: https://www.okd.io
[Typhoon]: https://typhoon.psdn.io
[podman]: https://podman.io
[quadlet]: https://docs.podman.io/en/latest/markdown/podman-systemd.unit.5.html
[Fedora Atomic Desktops]: https://fedoraproject.org/atomic-desktops/
[rpm-ostree]: https://coreos.github.io/rpm-ostree/
[Flatpak]: https://flatpak.org
[Silverblue]: https://fedoraproject.org/atomic-desktops/silverblue/
[Kinoite]: https://fedoraproject.org/atomic-desktops/kinoite/
[GNOME]: https://www.gnome.org
[KDE Plasma]: https://kde.org
[Universal Blue]: https://universal-blue.org/
[Aurora]: https://universal-blue.org/
[Bazzite]: https://bazzite.gg/
[Bluefin]: https://projectbluefin.io/
[KinoiteNightly]: https://tim.siosm.fr/blog/2023/01/20/introducing-kinoite-nightly-beta/
[KDE Applications]: https://kde.org/applications
[Flathub]: https://flathub.org/home
[toolbox]: https://github.com/coreos/toolbox
[distrobox]: https://github.com/89luca89/distrobox
[fedora-sysexts]: https://github.com/travier/fedora-sysexts
[sysexts-manager]: https://github.com/travier/sysexts-manager
