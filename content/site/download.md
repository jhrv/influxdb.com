+++
title = "downloads"
layout = "sidebar"
+++

# <a id="influxdb"></a>InfluxDB Downloads

## Version 0.9.5 (Stable)

#### OS X

- Via [Homebrew](http://brew.sh/)

> Note: The Homebrew version currently installs version 0.9.4.2. A Homebrew formula for version 0.9.5 will be available once [this PR](https://github.com/Homebrew/homebrew/pull/46231) has been merged.

		brew update
		brew install influxdb

#### Ubuntu & Debian

- 64-bit system install instructions

		wget https://s3.amazonaws.com/influxdb/influxdb_0.9.5_amd64.deb
		sudo dpkg -i influxdb_0.9.5_amd64.deb

MD5 checksum: `f768f325980d2e211bfb382dd045dc2e`

#### RedHat & CentOS

- 64-bit system install instructions

		wget https://s3.amazonaws.com/influxdb/influxdb-0.9.5-1.x86_64.rpm
		sudo yum localinstall influxdb-0.9.5-1.x86_64.rpm

MD5 checksum: `9a5a64fd0178f5a5fbdb71a6ec148bac`

#### Standalone Binary

- 64-bit system download & decompress instructions

		wget https://s3.amazonaws.com/influxdb/influxdb_0.9.5_x86_64.tar.gz
		tar xvfz influxdb_0.9.5_x86_64.tar.gz

MD5 checksum: `f145134464f0181163b3e0bd3fe37d0f`

#### Windows

> Note: The Windows installer currently installs version 0.9.4.2. A Windows build of version 0.9.5 will be available soon.

- <p>64-bit system install via the [InfluxDB Windows Installer](https://s3.amazonaws.com/influxdb/influxdb_0.9.4.2_amd64.msi)</p>

MD5 checksum: `8c6c0e198876772b40c036a96a94ba7e`

## Nightly Build
Nightly builds are created once-a-day, at 12:00 AM PT, using the top-of-tree of [master](https://github.com/influxdb/influxdb/tree/master) source code. These builds include the upcoming release number in the version string.

#### Ubuntu & Debian

- 64-bit system install instructions

        wget https://s3.amazonaws.com/influxdb/influxdb_nightly_amd64.deb
        sudo dpkg -i influxdb_nightly_amd64.deb

#### RedHat & CentOS

- 64-bit system install instructions

        wget https://s3.amazonaws.com/influxdb/influxdb-nightly-1.x86_64.rpm
        sudo yum localinstall influxdb-nightly-1.x86_64.rpm

#### Standalone Binary

- 64-bit system download & decompress instructions

		wget https://influxdb.s3.amazonaws.com/influxdb_nightly_x86_64.tar.gz
		tar xvfz influxdb_nightly_x86_64.tar.gz

### 32-Bit Packages
The industry is gradually [moving away from support for 32-bit x86 architectures](https://golang.org/doc/go1.5) so we do not provide packaged 32-bit binaries. However, we do endeavour to ensure the source can be compiled for a 32-bit x86 architecture at all times. To that end our [CI system](https://circleci.com/gh/influxdb/influxdb/tree/master) currently compiles 32-bit binaries and runs the unit test suite against the 32-bit build, in addition to the main 64-bit build. If compilation or unit testing for 32-bit architecture fails, we fix it.

However, we do reserve the right to break 32-bit compatibilty in the future, should design and implementation require it, but there are no plans to do so at this time.

### Deprecated Releases

Deprecated versions are no longer actively developed.

- [version 0.8](/docs/v0.8/introduction/installation.html)


# <a id="telegraf"></a>Telegraf Downloads

## Version 0.2.2

#### OS X

- Via [Homebrew](http://brew.sh/)

		brew update
		brew install telegraf

#### Ubuntu & Debian

- 64-bit system install instructions

		wget https://s3.amazonaws.com/get.influxdb.org/telegraf/telegraf_0.2.2_amd64.deb
		sudo dpkg -i telegraf_0.2.2_amd64.deb

MD5 checksum: `9c34466f5d514e1ceac3543ac2aa2ccf`

#### RedHat & CentOS

- 64-bit system install instructions

		wget https://s3.amazonaws.com/get.influxdb.org/telegraf/telegraf-0.2.2-1.x86_64.rpm
		sudo yum localinstall telegraf-0.2.2-1.x86_64.rpm

MD5 checksum: `ba6b796aa3bd38272da79d569dd5b925`

#### Standalone Binary

- 64-bit system download & decompress instructions

		wget https://s3.amazonaws.com/get.influxdb.org/telegraf/telegraf_linux_amd64_0.2.2.tar.gz
		tar xvfz telegraf_linux_amd64_0.2.2.tar.gz

MD5 checksum: `e850f2d3712aa077f4fc5d6aaf2aef57`

# <a id="chronograf"></a>Chronograf Downloads

## Version 0.3.2

#### OS X

- Via [Homebrew](http://brew.sh/)

> Note: The Homebrew version currently installs version 0.3.0. A Homebrew formula for version 0.3.2 will be available once [this PR](https://github.com/Homebrew/homebrew-binary/pull/278) has been merged.

		brew update
		brew install homebrew/binary/chronograf

#### Ubuntu & Debian

- 64-bit system install instructions

		wget https://s3.amazonaws.com/get.influxdb.org/chronograf/chronograf_0.3.2_amd64.deb
		sudo dpkg -i chronograf_0.3.2_amd64.deb

MD5 checksum: `1a8c09b6abf8276408a2b2a4e1eb7e84`

#### RedHat & CentOS

- 64-bit system install instructions

		wget https://s3.amazonaws.com/get.influxdb.org/chronograf/chronograf-0.3.2-1.x86_64.rpm
		sudo yum localinstall chronograf-0.3.2-1.x86_64.rpm

MD5 checksum: `3b3343822c35b110a4b82c6faca09ad5`

#### Standalone OS X Binary

- 64-bit system download & decompress instructions

		wget https://s3.amazonaws.com/get.influxdb.org/chronograf/chronograf-0.3.2-darwin_amd64.tar.gz
		tar xvfz chronograf-0.3.2-darwin_amd64.tar.gz

MD5 checksum: `6d65946bf759a91213f9e60eb9227278`

#### Windows

> Note: The Windows installer will install version 0.2.0. A Windows installer for version 0.3 will be available soon.

- <p>64-bit system install via the [Chronograf Windows Installer](https://s3.amazonaws.com/get.influxdb.org/chronograf/chronograf_0.2.0_amd64.msi)</p>

MD5 checksum: `e85f4b630004e9c8f2e2151b68ed6ab1`

## Usage

If you installed Chronograf via a Debian or RPM package, you should be able to simply run `sudo service chronograf start`.
The Chronograf startup script needs root permission to ensure that it can write to /var/log, but the actual executable runs as a normal user.

If you did not install Chronograf via a package, you can just directly run the executable, e.g.

```
/opt/chronograf/chronograf -config=/opt/etc/chronograf.toml
```

## Registration

Every install of Chronograf requires a free registration on InfluxData Enterprise. Registration allows us to improve release management and functionality for Chronograf.

<script>
    if (typeof Cookies.get("submitted") === 'undefined') {
        var inst = $('[data-remodal-id=download]').remodal();
        inst.open();

        $(document).on('confirmation', '.remodal', function () {
            var form = $("form#download");
            var url = form.attr("action") ;
            var data = form.serialize();
            var email = $("input#email");

            if (email.val() != "") {
                $.post(url, data);
                Cookies.set("submitted", true);
            }
        })
    }
</script>


