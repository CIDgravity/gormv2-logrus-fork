# Changelog

All notable changes to this project will be documented in this file.

## 1.3.0
### Added
- Rows affected as Logrus parameter
### Fixed
- Colorful option removed because Logrus doesn't work well when output is redirected to file
- Change SLOW SQL requests to add the "reason" parameter
- Remove new lines when logging
## 1.2.0
### Added
- Gorm options support
### Fixed
- upgrade dependencies for maintenance

## 1.1.2
### Fixed
- upgrade dependencies (this is a maintenance release)

## 1.1.1
### Fixed
- upgrade dependencies (this is a maintenance release)

## 1.1.0
### Added
- Missing log level management
- "SLOW SQL" Prefix on slow sql logs

## 1.0.0
### Added
- Gormlog library
- Example in readme