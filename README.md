## Intel QuickAssist for the Intel Atom Rangeley

This installation for the Intel Atom C2000
Test only on Debian 9.4 (Stretch)

Derived from Intel QuickAssist 1.5 Driver, available at:
https://01.org/packet-processing/intel%C2%AE-quickassist-technology-drivers-and-patches

Driver original available at:
https://01.org/sites/default/files/page/qatmux.l.2.6.0-60.tgz

This driver provides the QAT API, and can be used via OpenSSL ( https://github.com/01org/QAT_Engine) or via DPDK's cryptodev functionality.

## Compile driver

Install tools required for compiling the driver.

apt-get install gcc g++ make patch dpkg-dev build-essential pkg-config
apt-get install linux-headers-4.9.0-6-amd64
