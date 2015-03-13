coveralls.net
=============

[![GitHub version](https://badge.fury.io/gh/coveralls-net%2Fcoveralls.net.svg)](http://badge.fury.io/gh/coveralls-net%2Fcoveralls.net)
[![Build status](https://ci.appveyor.com/api/projects/status/github/coveralls-net/coveralls.net?branch=master&svg=true)](https://ci.appveyor.com/project/jdeering/coveralls-net-gmbph)
[![Coverage Status](https://coveralls.io/repos/coveralls-net/coveralls.net/badge.svg)](https://coveralls.io/r/coveralls-net/coveralls.net)
[![Code Quality](https://scan.coverity.com/projects/4516/badge.svg)](https://scan.coverity.com/projects/4516)

Coveralls uploader for .Net code coverage reporting

## Getting started

Coveralls is a service which keep track of code coverate statistics. The process is as follows

* Push your code to GitHub
* Build server builds, runs unit tests, and using `coveralls.net`, sends coverage information to [coveralls.io](http://coveralls.io)
* Your project's coveralls badge gets updated

For detailed instructions, please visit the [wiki](https://github.com/coveralls-net/coveralls.net/wiki)

## Supported Frameworks

#### Coverage Tools

* [OpenCover](https://github.com/sawilde/opencover)

#### CI Services

* [AppVeyor](http://www.appveyor.com/)
* [Jenkins](http://jenkins-ci.org/)

## Planned

These are the remaining targets, but I'm not sure how far I will be able to get on my own. If you would like to help, please
fork this repository

#### Coverage Tools

* [SharpCover](https://github.com/gaillard/SharpCover)
* [Mono Code Coverage (monocov)](http://www.mono-project.com/docs/debug+profile/profile/code-coverage/)
* [Visual Studio Coverage](http://msdn.microsoft.com/en-us/library/dd299398%28v=vs.90%29.aspx)
* [NCover](https://www.ncover.com/)

#### CI Services

* [Travis CI](https://travis-ci.org)
* [Bamboo](https://www.atlassian.com/software/bamboo)

## Versioning

<b>coveralls.net</b> will be maintained under the Semantic Versioning guidelines as much as possible. Releases will be numbered with the following format:

`<major>.<minor>.<build>`

and constructed with the following guidelines:

* Breaking backward compatibility bumps the major (resetting the minor and build)
* New additions without breaking backward compatibility bumps the minor (resetting the build)
* Bug fixes and misc changes increase the build number

For more information on SemVer, please visit http://semver.org/.


## Bug tracker

Have a bug or a feature request? [Please open a new issue](https://github.com/coveralls-net/coveralls.net/issues). Before opening a new issue, please search for existing issues.


## Contributing

Please submit all pull requests against WIP branches. You must include all relevant unit tests for any bug fixes or new features.

Thanks!


## Authors

**Jason Deering**

+ http://twitter.com/jasondeering
+ http://github.com/jdeering

## License

Licensed under the GNU General Public License, Version 3.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License at:

* http://www.gnu.org/licenses/gpl-3.0.txt

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
