# vlingo-platform

[![Build Status](https://travis-ci.org/vlingo/vlingo-platform.svg?branch=master)](https://travis-ci.org/vlingo/vlingo-platform)

Provides vlingo/platform central "build all" and other control. [Read about the vlingo/platform](https://forcomprehension.com/2017/12/23/vlingo-platform/) and about [its architecture](https://forcomprehension.com/2018/01/24/vlingo-platform-architecture-part1/).

Use "mvn install" from here with the pom.xml and the entire platform to build.

```
console:vlingo-platform> mvn install
```

## maintaining the libraries

- see [build.gradle](build.gradle) for the list of repos, versions and replacement regexes
- adjust the config
- run `gradle` or `./gradlew`
- review and commit the repos

License (See LICENSE file for full license)
-------------------------------------------
Copyright © 2012-2018 Vaughn Vernon. All rights reserved.

This Source Code Form is subject to the terms of the
Mozilla Public License, v. 2.0. If a copy of the MPL
was not distributed with this file, You can obtain
one at https://mozilla.org/MPL/2.0/.
