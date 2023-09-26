# Wordpress via Podman Quadlets on CoreOS

📝 **Read the [full blog post] that explains everything here!**

[full blog post]: https://major.io/p/quadlets-replace-docker-compose/

The goal here is to launch a very minimal [Wordpress] stack using [quadlets] on [Fedora
CoreOS] via [VULTR] that updates itself and self-heals when a container exits
unexpectedly. Configurations are deployed via [ignition] using a [butane] configuration
source.

If you're in a hurry, just install a couple of packages on [Fedora] and get going!

```console
# Install some packages.
$ sudo dnf -y install butane vultr-cli

# Get your vultr API key: https://my.vultr.com/settings/#settingsapi
$ ./launch-instance
```

[Wordpress]: https://wordpress.org/
[quadlets]: https://www.redhat.com/sysadmin/quadlet-podman
[Fedora CoreOS]: https://fedoraproject.org/coreos/
[VULTR]: https://www.vultr.com/?ref=9544589-8H
[ignition]: https://coreos.github.io/ignition/
[butane]: https://coreos.github.io/butane/
[Fedora]: https://fedoraproject.org/
