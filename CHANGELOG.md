## [TBD]
### Changed
* Update Checkstyle configuration to ignore overriden parameter names and parameter numbers, as well as limiting the number of characters on a line to 120, ignoring where classes should be final and changing the indentation for switch statements from 2 to 0.

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
