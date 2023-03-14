---
date: 2023-03-14T14:15:10+00:00
title: Git
pre: "<b>1.1 </b>"
weight: 10
---

## Install Git

Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

{{< tabs groupId="git" >}}
{{% tab name="Windows" %}}

The easiest thing for Windows is to [download the executable from the official website](https://git-scm.com/download/win), 32 or 64 bits depending on your computer.

Once finished, we will have installed both Git and Git Bash (terminal) on Windows. In said *Git Bash terminal* we can enter the following command to check which version of Git we have installed:

```bash
git --version
git version 2.33.0.windows.2
```

{{% /tab %}}
{{% tab name="Mac" %}}

There are several ways to install Git on a Mac. Probably the easiest is to install the Xcode Command Line tools. On Mavericks (10.9 or higher) you can do this from the Terminal if you are trying to run git for the first time. If you don't have it installed, it will ask you if you want to install it.

If you want a more up-to-date version, you can do it from a binary installer. A Git installer for OSX is maintained on the Git website. You can download it at [http://git-scm.com/download/mac](http://git-scm.com/download/mac)

{{% /tab %}}
{{% tab name="Linux" %}}

If you want to install Git on Linux via a binary installer, you can usually do so using the basic package management tool that comes with your distribution. If you are on Fedora for example, you can use yum:

```bash
yum install git
```

If you're on a Debian-based distribution like Ubuntu, you can use apt-get:

```bash
apt-get install git
```

For additional options, the Git web page has installation instructions on different Unix types. You can find this information at [http://git-scm.com/download/linux](http://git-scm.com/download/linux)

{{% /tab %}}
{{< /tabs >}}