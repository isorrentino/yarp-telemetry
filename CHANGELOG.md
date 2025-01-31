# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2021-05-19

- Added the possibility to specify the time of a ``Record`` with ``push_back``.
- Added the possibility to enable the zlib compression.
- Fixed yarp-telemetry.ini generation.
- Fixed load of `telemetryDeviceDumper` plugin.
- Added the log from these interfaces in the `telemetryDeviceDumper`:
  - `yarp::dev::IMotorEncoders`
  - `yarp::dev::IPidControl`
  - `yarp::dev::IAmplifierControl`
  - `yarp::dev::IControlMode`
  - `yarp::dev::IInteractionMode`
  - `yarp::dev::ITorqueControl`
- Added check of the existence of the path specified in the configuration.

## [0.1.0] - 2021-04-02

First release of `yarp-telemetry`, compatible with YARP 3.4.

