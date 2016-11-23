OSMLR is an open standard. There are no royalties, restrictions or other requirements for implementing it.

The OSMLR specification is developed [in the GitHub repository](https://github.com/opentraffic/osmlr-tile-spec) by creating and discussing issues and pull requests.

Making changes
--------------

Changes can be proposed either by [filing a new issue](https://github.com/opentraffic/osmlr-tile-spec/issues/new) or by making a pull request. The choice of which method is appropriate should be governed by the magnitude of the proposed change in terms of the [semantic version](http://semver.org/). For example:

* Small changes, which are compatible with previous releases and would require a new PATCH level release, may be submitted as pull requests. This might include fixes to spelling or grammar, clarifications to the documentation or comments, or additional detail or examples.
* Larger changes should be proposed as an issue first, as these may require careful review and will require a MINOR or MAJOR level release. In general, proposed changes should avoid requiring a new MAJOR release unless absolutely necessary to define any new functionality.

Please be considerate and read through prior and existing issues and pull requests before creating a new one.

Releasing new versions
----------------------

New versions of the specification will be released by creating a tag with the name `vMAJOR.MINOR.PATCH`. This version is guaranteed not to change, and is suitable for inclusion into downstream projects as a submodule. Any changes to the specification will be assigned _at least_ a new PATCH level version.
