# Humilis plug-in to deploy an Elasticache cluster

[![PyPI](https://img.shields.io/pypi/v/humilis-elasticache.svg?style=flat)](https://pypi.python.org/pypi/humilis-elasticache)

A [humilis][humilis] plug-in layer that deploys an [Elasticache cluster][elasticache].

[elasticache]: https://aws.amazon.com/elasticache/
[humilis]: https://github.com/humilis/humilis


## Installation


```
pip install humilis-elasticache
```


To install the development version:

```
pip install git+https://github.com/humilis/humilis-elasticache
```


## Development

Assuming you have [virtualenv][venv] installed:

[venv]: https://virtualenv.readthedocs.org/en/latest/

```
make develop
```

Configure humilis:

```
make configure
```


## Testing

You can test the deployment of an Elasticache cluster with:

```
make test
```

The test suite should destroy the deployed cluster automatically, but you 
can make sure you are not leaving any infrastructure behind by manually 
running:

```bash
make delete
```


## More information

See [humilis][humilis] documentation.


## Contact

If you have questions, bug reports, suggestions, etc. please create an issue on
the [GitHub project page][github].

[github]: http://github.com/humilis/humilis-elasticache


## License

This software is licensed under the [MIT license][mit].

[mit]: http://en.wikipedia.org/wiki/MIT_License

See [License file][LICENSE].

[LICENSE]: https://github.com/humilis/humilis-elasticache/blob/master/LICENSE.txt


© 2016 German Gomez-Herrero, [Find Hotel][fh] and others.

[fh]: http://company.findhotel.net
