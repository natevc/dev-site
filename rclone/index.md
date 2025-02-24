---
title: "dev.natevc.com/rclone"
description: "Rclone syncs your files to cloud storage: Google Drive, S3, Swift, Dropbox, Google Cloud Storage, Azure, Box and many more."
type: page
notoc: true
---
![logo](/dev-natevc-logo.svg)

# Rclone Services

- About rclone
- What can rclone do for you?
- What features does rclone have?
- What providers does rclone support?
{{< rem MAINPAGELINK >}}

## About rclone {#about}

Rclone is a command-line program to manage files on cloud storage. It
is a feature-rich alternative to cloud vendors' web storage
interfaces. Over 70 cloud storage products support
rclone including S3 object stores, business & consumer file storage
services, as well as standard transfer protocols.

Rclone has powerful cloud equivalents to the unix commands rsync, cp,
mv, mount, ls, ncdu, tree, rm, and cat. Rclone's familiar syntax
includes shell pipeline support, and `--dry-run` protection. It is
used at the command line, in scripts or via its API.

Users call rclone *"The Swiss army knife of cloud storage"*, and
*"Technology indistinguishable from magic"*.

Rclone really looks after your data. It preserves timestamps and
verifies checksums at all times. Transfers over limited bandwidth;
intermittent connections, or subject to quota can be restarted, from
the last good file transferred. You can
check the integrity of your files. Where
possible, rclone employs server-side transfers to minimise local
bandwidth use and transfers from one provider to another without
using local disk.

Virtual backends wrap local and cloud file systems to apply
encryption,
compression,
chunking,
hashing and
joining.

Rclone mounts any local, cloud or
virtual filesystem as a disk on Windows,
macOS, linux and FreeBSD, and also serves these over
SFTP,
HTTP,
WebDAV,
FTP and
DLNA.

Rclone is mature, open-source software originally inspired by rsync
and written in Go. The friendly support
community is familiar with varied use cases. Official Ubuntu, Debian,
Fedora, Brew and Chocolatey repos. include rclone. For the latest
version downloading from rclone.org is recommended.

Rclone is widely used on Linux, Windows and Mac. Third-party
developers create innovative backup, restore, GUI and business
process solutions using the rclone command line or API.

Rclone does the heavy lifting of communicating with cloud storage.

## What can rclone do for you? {#what}

Rclone helps you:

- Backup (and encrypt) files to cloud storage
- Restore (and decrypt) files from cloud storage
- Mirror cloud data to other cloud services or locally
- Migrate data to the cloud, or between cloud storage vendors
- Mount multiple, encrypted, cached or diverse cloud storage as a disk
- Analyse and account for data held on cloud storage using lsf, ljson, size, ncdu
- Union file systems together to present multiple local and/or cloud file systems as one

## Features {#features}

- Transfers
    - MD5, SHA1 hashes are checked at all times for file integrity
    - Timestamps are preserved on files
    - Operations can be restarted at any time
    - Can be to and from network, e.g. two different cloud providers
    - Can use multi-threaded downloads to local disk
- Copy new or changed files to cloud storage
- Sync (one way) to make a directory identical
- Bisync (two way) to keep two directories in sync bidirectionally
- Move files to cloud storage deleting the local after verification
- Check hashes and for missing/extra files
- Mount your cloud storage as a network disk
- Serve local or remote files over HTTP/WebDav/FTP/SFTP/DLNA
- Experimental Web based GUI

## Links

  * {{< icon "fa fa-home" >}} [Home page](https://rclone.org/)
  * {{< icon "fab fa-github" >}} [GitHub project page for source and bug tracker](https://github.com/rclone/rclone)
  * {{< icon "fa fa-comments" >}} [Rclone Forum](https://forum.rclone.org)
  * {{< icon "fas fa-cloud-download-alt" >}}[Downloads](/downloads/)
  * [dev.natevc.com Rclone Services Privacy Policy](./privacy)

## Attribution

This document is based on https://rclone.org/ and is used under the MIT License.

Copyright (c) 2014-2025 Nick Craig-Wood