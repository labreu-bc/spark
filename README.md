This is a fork of https://github.com/robinhood/spark. Full credits go to the original authors.
======

This repository is only meant to serve as a maintenance update over the original, in order to allow users of this lib to disable jetifier.

If [this PR](https://github.com/robinhood/spark/pull/82) gets merged, i'll archive this repo.

Download
--------
Add jitpack maven repo
Gradle:

```groovy
repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}

dependencies {
	        implementation 'com.github.labreu-bc:spark:1.3.0'
	}
```



License
--------

    Copyright 2016 Robinhood Markets, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
