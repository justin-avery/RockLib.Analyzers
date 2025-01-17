# RockLib.Logging.Analyzers Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.0.2 - 2021-07-21

#### Changed

- RockLib0000: Include base classes when identifying public properties.
- RockLib0000: Look for calls to `SafeToLogAttribute.Decorate` and `NotSafeToLogAttribute.Decorate` when determining if a type or property has been marked as safe to log.

#### Added

- Analyzer for RockLib0006: Caught exception should be logged.
- Analyzer for RockLib0007: Unexpected extended properties object.

## 1.0.1 - 2021-07-13

#### Added

- Adds analyzer and codefix for RockLib0005: No log level specified

#### Fixed

- Be able to analyze extended properties when defined as a parameter, not just as a local variable

## 1.0.0 - 2021-06-09

#### Added

- Adds analyzer for RockLib0000: Extended property not marked as safe to log
- Adds analyzer and codefix for RockLib0001: Use sanitizing logging method
