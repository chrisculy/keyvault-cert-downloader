# README (Logos Specific)

This contains Logos specific information that is not relevant/suitable for the public.

## Publishing

There is a GitHub Actions workflow that will automatically publish a new version of the package to pypi whenever a tag is pushed. Ensure the version in `setup.cfg` matches the tag so that the package can be published successfully to PyPI and does not conflict with a previously published version.

The API token used for publishing is stored as the `PYPI_API_TOKEN` GitHub Actions secret and is also available in [PasswordManager](https://passwordmanager.lrscorp.net/app/#/secret/9154/)