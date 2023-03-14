---
date: 2023-03-14T14:05:10+00:00
title: Node.js & NPM
pre: "<b>1.2 </b>"
weight: 15
---

## Install Node.js & NPM

Node.js is a cross-platform, open-source server environment that can run on Windows, Linux, Unix, macOS, and more. Node.js is a back-end JavaScript runtime environment, runs on the V8 JavaScript Engine, and executes JavaScript code outside a web browser.

There are 2 versions of Node.js to be aware of, the LTS version Node.js and normal Node.js.

It is recommended to install/configure the LTS Node.js version. LTS is an acronym for Long-Term Support, and is applied to release lines (yes, that's plural) that will be supported and maintained by the Node. js project for an extended period of time.

{{< tabs groupId="node" >}}
{{% tab name="Windows" %}}

The easiest thing for Windows is to [download the executable from the official website](https://nodejs.org/en/download/), 32 or 64 bits depending on your computer.

Once finished, you will have Node.js & NPM configured on your Windows. To check which version of Node you have installed, you can enter the Windows terminal or CMD (command line), and type the following command to check:

```bash
node -v
v16.13.1
```

```bash
npm -v
8.1.2
```

{{% /tab %}}
{{% tab name="Mac" %}}

The easiest thing for Mac is to [download the executable .pkg from the official website](https://nodejs.org/en/download/).

Once finished, you will have Node.js & NPM configured on your Mac. To check which version of Node you have installed, you can enter the terminal and type the following command to check:

```bash
node -v
v16.13.1
```

```bash
npm -v
8.1.2
```

{{% /tab %}}
{{% tab name="Linux" %}}

The easier way is to use the apt package manager. Refresh your local package index first:

```bash
sudo apt update
```

Then install Node.js:

```bash
sudo apt install nodejs
```

Check that the install was successful by querying node for its version number:

```bash
node -v
v16.13.1
```

```bash
npm -v
8.1.2
```

{{% /tab %}}
{{< /tabs >}}