# React Native Dropdown Picker 5.x

<p float="left">
    <img src="https://user-images.githubusercontent.com/56504893/116790110-e0b36880-aac7-11eb-9ebd-196acee64f7a.png" width="270" alt="Screenshot">
    <img src="https://user-images.githubusercontent.com/56504893/116789802-faec4700-aac5-11eb-837b-86f18cbfcf3d.png" width="270" alt="Screenshot">
    <img src="https://user-images.githubusercontent.com/56504893/116789839-2c651280-aac6-11eb-99e0-b43b608ed8c7.png" width="270" alt="Screenshot">
</p>

# Documentation
**The documentation has been moved to https://hossein-zare.github.io/react-native-dropdown-picker-website/**

# Donation
**[✨ Support us to devote more time to this project - Buy me a coffee](https://www.buymeacoffee.com/hossein_zare)**

<p align="left">
    <a href="https://www.buymeacoffee.com/hossein_zare"><img src="https://user-images.githubusercontent.com/56504893/145917502-bb2ac04d-7ca7-46b0-880f-a4f62b48937f.png" width="200" alt="Donation"></a>
</p>

# Merge and Release Process

## Branches in use

### Development

PRs should be made against and merged into the [`dev-5.x`](https://github.com/hossein-zare/react-native-dropdown-picker) branch, which is set as the `default` branch on github.

### Release

Releases are currently made from the [`5.x`](https://github.com/hossein-zare/react-native-dropdown-picker/tree/5.x) branch.

## Release Process

To make a new release, follow these steps:

* Verify the development branch has all the changes desired in a release and works well
* Make and merge a final PR into development branch that increments the version number in `package.json`
* Make and merge a PR from the development branch to the release branch
* Using the GitHub web UI, draft a new release using tag name `vx.x.x` (replace the `x` values as appropriate of course), with the release branch as the target, with release name `vx.x.x` (again, with appropriate numbers in place of `x` of course)
* Verify in the GitHub Actions panel for the repository that NPM publish succeeded
