## [1.2.2] - 2019-01-07
### Changed
* Updated Checkstyle configuration to ignore overriden parameter names and parameter numbers, as well as limit the number of characters on a line to 120, ignore where classes should be final and check that indentation for switch statements is 0 instead of 2.

## [1.2.1] - 2018-07-13
### Fixed
* Re-instated "jar" as package type, not pom (mistake in 1.2.0 release).

## [1.2.0] - 2018-07-13 [YANKED]
### Changed
* Moved to Sonatype's updated recommendations for publishing artifacts to Maven Central. See [#6](https://github.com/HotelsDotCom/hotels-oss-plugin-config/issues/6).
* Updated `nexus-staging-maven-plugin` version to 1.6.8. See [#4](https://github.com/HotelsDotCom/hotels-oss-plugin-config/issues/4).

## [1.1.0] - 2017-07-12
### Added
* A change log.

### Changed
* Removed the redundantThrows check from hotels-checkstyle.xml as this was removed from Checkstyle in version 6.2. 
