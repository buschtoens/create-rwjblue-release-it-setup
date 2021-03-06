# create-rwjblue-release-it-setup

Simple npm init / yarn create bin package to add release-it setup used by rwjblue.

This will do the following:

* add `release-it` config to the `package.json`
* install required dependencies,
* add a `CHANGELOG.md`
* add a `RELEASE.md`
* update your repositories labels with my "go to" defaults

## Usage

When you want to set up a repo with `release-it`, you can run:

```
# in a yarn repo
yarn create rwjblue-release-it-setup

# in an npm repo
npm init rwjblue-release-it-setup
```

If you'd like to update an existing repo to use the latest and greatest setup, you can run:

```
# in a yarn repo
yarn create rwjblue-release-it-setup --update

# in an npm repo
npm init rwjblue-release-it-setup --update
```

If you'd like to run only the label sync, you can do that with:

```
# in a yarn repo
yarn create rwjblue-release-it-setup --labels-only

# in an npm repo
npm init rwjblue-release-it-setup --labels-only
```

## License

This project is licensed under the [MIT License](LICENSE.md).
