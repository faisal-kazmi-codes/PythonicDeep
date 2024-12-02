
## Installation


```shell
pip install --upgrade deepl
```

If you need to modify this source code, install the dependencies using poetry:

```shell
poetry install
```

On Ubuntu 22.04 an error might occur: `ModuleNotFoundError: No module named 
'cachecontrol'`. Use the workaround `sudo apt install python3-cachecontrol` as
explained in this [bug report][bug-report-ubuntu-2204].

### Requirements

The library is tested with Python versions 3.6 to 3.11.

The `requests` module is used to perform HTTP requests; the minimum is version
2.0.

Starting in 2024, we will drop support for older Python versions that have
reached official end-of-life. You can find the Python versions and support
timelines [here][python-version-list].
To continue using this library, you should update to Python 3.8+.

#
The recognized commands are:

| Command   | Description                                            |
| :-------- | :----------------------------------------------------- |
| text      | translate text(s)                                      |
| document  | translate document(s)                                  |
| usage     | print usage information for the current billing period |
| languages | print available languages                              |
| glossary  | create, list, and remove glossaries                    |

For example, to translate text:

```shell
```

Wrap text arguments in quotes to prevent the shell from splitting sentences into
words.

## Development

[api-docs-csv-format]: https://www.deepl.com/docs-api/managing-glossaries/supported-glossary-formats/?utm_source=github&utm_medium=github-python-readme

[api-docs-xml-handling]: https://www.deepl.com/docs-api/handling-xml/?utm_source=github&utm_medium=github-python-readme

[api-docs-context-param]: https://www.deepl.com/docs-api/translating-text/?utm_source=github&utm_medium=github-python-readme

[api-docs-lang-list]: https://www.deepl.com/docs-api/translating-text/?utm_source=github&utm_medium=github-python-readme

[api-docs-glossary-lang-list]: https://www.deepl.com/docs-api/managing-glossaries/?utm_source=github&utm_medium=github-python-readme

[bug-report-ubuntu-2204]: https://bugs.launchpad.net/ubuntu/+source/poetry/+bug/1958227

[create-account]: https://www.deepl.com/pro?utm_source=github&utm_medium=github-python-readme#developer

[deepl-mock]: https://www.github.com/DeepLcom/deepl-mock

[issues]: https://www.github.com/DeepLcom/deepl-python/issues

[pypi-project]: https://pypi.org/project/deepl/

[pro-account]: https://www.deepl.com/pro-account/?utm_source=github&utm_medium=github-python-readme

[python-version-list]: https://devguide.python.org/versions/

[requests-proxy-docs]: https://docs.python-requests.org/en/latest/user/advanced/#proxies

[requests-verify-ssl-docs]: https://docs.python-requests.org/en/latest/user/advanced/#ssl-cert-verification
