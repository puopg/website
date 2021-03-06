{{i18n.install_nightly_intro}}

The easiest way of installing a nightly build is via our shell script:

```sh
curl -o- -L https://yarnpkg.com/install.sh | bash -s -- --nightly
```

An Ubuntu/Debian repository of the nightly builds is also available. To enable it, run the following commands:

```sh
sudo apt-key adv --fetch-keys http://dl.yarnpkg.com/debian/pubkey.gpg
echo "deb http://nightly.yarnpkg.com/debian/ nightly main" | sudo tee /etc/apt/sources.list.d/yarn-nightly.list
sudo apt update && sudo apt install yarn
```

On Windows, the [Windows installer](https://nightly.yarnpkg.com/latest.msi) can be used.
