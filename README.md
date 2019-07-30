Fork of https://github.com/hashicorp/go-version

# Versioning Library for Go

go-version is a library for parsing versions and version constraints,
and verifying versions against a set of constraints. go-version
can sort a collection of versions properly, handles prerelease/beta
versions, can increment versions, etc.

Versions used with go-version should follow [SemVer](http://semver.org/),
though arbitrary alphanumeric prefixes with hyphens and tildes are supported
and versions may have fewer than three segments.
