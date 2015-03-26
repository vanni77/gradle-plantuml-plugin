Gradle PlantUML Pluging
=======================
Renders plant.uml files in a project.

[![Build Status](https://travis-ci.org/dirkraft/gradle-plantuml-plugin.svg?branch=master)](https://travis-ci.org/dirkraft/gradle-plantuml-plugin)


## Usage ##

```gradle
buildscript {
    repositories {
        maven {
            url 'https://oss.sonatype.org/content/repositories/snapshots/'
        }
    }
    dependencies {
        classpath 'com.github.dirkraft.gradle:gradle-plantuml-plugin:0.0.1-SNAPSHOT'
    }
}

apply plugin: 'PlantUml'
```

Place uml files in `assets/`

```bash
gradle renderPlantUml
```

Rendered PNGs and SVGs placed alongside uml.


## License ##


```
The MIT License (MIT)

Copyright (c) 2015 Jason Dunkelberger (a.k.a dirkraft)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```