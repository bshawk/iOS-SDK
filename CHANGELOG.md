## 2.0.1 (July 15, 2014)

Bugfixes:

 - Hanging on beacons ranging (100% CPU usage) issue solved.


## 2.0.0 (June 6, 2014)

Features:
	
	- Estimote Cloud Integration implemented
	- Added temperature and accelerometer support
	- Added motionUUID to ESTBeacon
	- Support for firmware EstimoteOS 2.0 and up
	- Connection status handeld better
	- Improved examples app
	
Refactoring:
	- ESTBeacon method name changes:
		- connectToBeacon -> connect
		- disconnectBeacon -> disconnect
		- writeBeaconName:withCompletion: -> writeName:completion:
		- writeBeaconProximityUUID:withCompletion: -> writeProximityUUID:completion:
		- writeBeaconMajor:withCompletion: -> writeMajor:completion:
		- writeBeaconMinor:withCompletion: -> writeMinor:completion
		- writeBeaconAdvInterval:withCompletion: -> writeAdvInterval:completion:
		- writeBeaconPower:withCompletion: -> writePower:completion:
		- updateBeaconFirmwareWithProgress:andCompletion: -> updateFirmwareWithProgress:completion:

## 1.3.0 (January 25, 2014)

Features:

  - Unlocked Proximity UUID

Bugfixes:

  - Bug fixes

## 1.2.0 (December 9, 2013)

Features:

  - ESTBeacon class cleaned (flat structure with iBeacon property removed)
  - Library documentation updated

Bugfixes:

  - Corrected name of DistanceDemo project
  
## 1.1.0 (December 2, 2013)

Features:

  - Frequency change to Advertising Interval (Naming convention - check DOC)
  - Checking for firmware update, with update details info
  - Changlog for tags added
  - library name changed from libEstimoteSDK7.a to libEstimoteSDK.a

Bugfixes:

  - Variable type for Major, Minor, Power, Adv. Interval change to unsigned short
  - startEstimoteBeaconsDiscoveryForRegion: corrected beacon array refresh


## 1.0.0 (November 7, 2013)

Features:

  - Ranging and monitoring Estimote beacons
  - Beacon connection support 
  - Read/Write of Major, Minor, Power and Frequency (Battery, Firmware and Hardware version - readonly)
  - Beacon Firmware update support
  
