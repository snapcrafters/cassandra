# This repository is currently unmaintained

The snap available in the snapstore is currently built from
https://code.launchpad.net/cassandra-snap

The launchpad repository is currently orphan. Please, file an issue in this
repository if you are willing to adopt it.

<h1 align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Cassandra_logo.svg/1280px-Cassandra_logo.svg.png" alt="Cassandra" height="256px">
</h1>

<p align="center"><b>This is the snap for Cassandra</b>, a highly-scalable partitioned row store. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.</p>
<p align="center">
<a href="https://build.snapcraft.io/user/snapcrafters/cassandra"><img src="https://build.snapcraft.io/badge/snapcrafters/cassandra.svg" alt="Snap Status"></a><br>(<a href="https://bugs.launchpad.net/launchpad/+bug/1702130">bug #1702130</a>)
</p>

## Install

    snap install cassandra
    snap connect cassandra:mount-observe

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

Check the status:

    systemctl status snap.cassandra.cassandra.service

Set a custom configuration:

    cat cassandra.yaml | sudo /snap/bin/cassandra.config-set cassandra.yaml

<p align="center">Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with :gift_heart: by Snapcrafters</p>

## Remaining tasks

Snapcrafters ([join us](https://forum.snapcraft.io/t/join-snapcrafters/1325)) are working to land snap install documentation and the [snapcraft.yaml](https://github.com/snapcrafters/discord/blob/master/snap/snapcraft.yaml) upstream so Discord can authoritatively publish future releases.

  - [x] Fork the [Snapcrafters template]() repository to your own GitHub account
  - [x] Create a snap that runs in `devmode`
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [x] Add a screenshot to this `README.md`
  - [x] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [-] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io)
  - [x] Request your GitHub repository is forked to the Snapcrafters organisation and configured for automated builds
  - [x] Add the provided Snapcraft build badge to this `README.md`
  - [x] Publish the snap in the Snap store stable channel
  - [x] Update the install instructions in this `README.md`
  - [-] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io)
  - [ ] Submit a pull request or patch upstream that adds snap install documentation
  - [ ] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Add upstream contact information to the `README.md`
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
 - [-] Ask the Snap Advocacy team to celebrate the snap

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

## The Snapcrafters

| [![Evan Dandrea](http://gravatar.com/avatar/b9c6dc703231efc4e307d3c59d1f9321?s=128)](https://github.com/evandandrea/) |
| :---: |
| [Evan Dandrea](https://github.com/evandandrea/) |
