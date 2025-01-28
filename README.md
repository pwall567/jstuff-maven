# jstuff-maven

[![Build Status](https://github.com/pwall567/jstuff-maven/actions/workflows/deploy.yml/badge.svg)](https://github.com/pwall567/jstuff-maven/actions/workflows/deploy.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maven Central](https://img.shields.io/maven-central/v/io.jstuff/jstuff-maven?label=Maven%20Central)](https://search.maven.org/search?q=g:%22io.jstuff%22%20AND%20a:%22jstuff-maven%22)

Maven parent POM for jstuff projects

Includes plugin definitions for deployment to Sonatype Central.

The current version is 1.0 &ndash; the default Java version is 1.8.

## Usage

```xml
  <parent>
    <groupId>io.jstuff</groupId>
    <artifactId>jstuff-maven</artifactId>
    <version>1.0</version>
  </parent>
```

Peter Wall

2025-01-28
