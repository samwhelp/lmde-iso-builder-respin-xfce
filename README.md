

# Home

| Link | GitHub |
| ---- | ------ |
| [lmde-iso-builder-respin-xfce](https://samwhelp.github.io/lmde-iso-builder-respin-xfce/) | [GitHub](https://github.com/samwhelp/lmde-iso-builder-respin-xfce) |




## Subject

* [Combination](#combination)
* [Environment](#environment)
* [Start](#start)
* [Clone](#clone)
* [Usage](#usage)
* [Config Files](#config-files)
* [Package Install List](#package-install-list)
* [Link](#link)




## Combination

| Project |
| ------- |
| [lmde-iso-builder-template](https://github.com/samwhelp/lmde-iso-builder-template) |
| `+` |
| [lmde-iso-builder-remix-xfce](https://github.com/samwhelp/lmde-iso-builder-remix-xfce) |
| `=` |
| [lmde-iso-builder-respin-xfce](https://github.com/samwhelp/lmde-iso-builder-respin-xfce) |




## Environment

* `Debian 13`




## Start

Open Terminal , and run to install `git` and `make`

``` sh
sudo apt-get install git make
```




## Clone

Run to clone [lmde-iso-builder-respin-xfce](https://github.com/samwhelp/lmde-iso-builder-respin-xfce)

``` sh
git clone https://github.com/samwhelp/lmde-iso-builder-respin-xfce
```

Run to change dir `lmde-iso-builder-respin-xfce`

``` sh
cd lmde-iso-builder-respin-xfce
```




## Usage

* [Help](#help)
* [Prepare](#prepare)
* [Build](#build)
* [Clean](#clean)




## Help

Run

``` sh
make
```

Or run

``` sh
make help
```

Show

```
Usage:
	$ make [action]

Example:
	$ make
	$ make help

	$ make prepare
	$ make build
	$ make clean

```




## Prepare

Run the following command to install the packages required to create an ISO file.

``` sh
make prepare
```




## Build

Only need to execute the following command to create an ISO file.

``` sh
make build
```




## Clean

Run to clean up previous builds.

``` sh
make clean
```




## Config Files

| Config Files |
| ------------ |
| [~/.config](https://github.com/samwhelp/lmde-iso-builder-respin-xfce/tree/main/template/asset/overlay/etc/skel/.config) |
| [/etc/dconf/db/lmde.d](https://github.com/samwhelp/lmde-iso-builder-respin-xfce/tree/main/template/asset/overlay/etc/dconf/db/lmde.d) |
| [/usr/share/glib-2.0/schemas](https://github.com/samwhelp/lmde-iso-builder-respin-xfce/tree/main/template/asset/overlay/usr/share/glib-2.0/schemas) |




## Package Install List

> Please check the folder

* [template/asset/package/install](https://github.com/samwhelp/lmde-iso-builder-respin-xfce/tree/main/template/asset/package/install)

> Ubuntu Community Help Wiki / [MetaPackages](https://help.ubuntu.com/community/MetaPackages)




## Link

| Link | GitHub |
| ---- | ------ |
| [Lmde Xfce Adjustment](https://samwhelp.github.io/lmde-xfce-adjustment/) | [GitHub](https://github.com/samwhelp/lmde-xfce-adjustment) |
| [Lmde Adjustment](https://samwhelp.github.io/lmde-adjustment/) | [GitHub](https://github.com/samwhelp/lmde-adjustment) |




## Samwhelp

* [GitHub](https://github.com/samwhelp)
