Forked from <https://github.com/UbiquityRobotics/fiducials>

Main changes:
- Disable use of variance for weighing tags
- Simple outlier rejection
- Add `/fiducial_ready` publisher
- Remove minimum number of tags requirement for localizing
- Some bug fixes

Additional published topics:
`/fiducial_ready`: Whether a valid pose is ready after clearing map
