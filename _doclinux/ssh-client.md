---
title:  "Login to the command-line through ssh"
categories: admin user
---

Use a terminal to log in via ssh:

```bash
$ ssh <UPI>@<VM name>
```

If you have admin privileges on the VM (sudo) you need to login through [2-factor authentication]({{ site.baseurl }}{% link _doclinux/two-factor-authentication.md %}). Otherwise just use your University password to log in.

Example:

```bash
$ ssh mfel395@cerdkroprd01.its.auckland.ac.nz
```