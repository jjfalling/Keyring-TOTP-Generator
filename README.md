# Keyring-TOTP-Generator
Simple Python TOTP code generator that stores TOTP secrets in your keyring

Supported keyrings can be found [here](https://pypi.python.org/pypi/keyring#what-is-python-keyring-lib). You can also specify the [keyring settings](https://pypi.python.org/pypi/keyring#customize-your-keyring-by-config-file
) in a config file. Run with the -d flag for the config root path and the current keyring service.

Setproctitle is an optional dependency.

Run with the --help flag for more information.


#### Development
Install the test requirements with `pip install -e .[test]`. Run the tests with pytest.