# TweakScale Companion :: Legacy

Adds (up to date) TweakScale /L patches for the older patches that were left behind no the main TweakScale distribution.


## Installation Instructions

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**:
	+ Delete `<KSP_ROOT>/GameData/TweakScaleCompanion/Legacy`
* Extract the package's `GameData/` folder into your KSP's as follows:
	+ `<PACKAGE>/GameData/TweakScaleCompanion/Legacy` --> `<KSP_ROOT>/GameData/TweakScaleCompanion`
		- Overwrite any preexisting file.

The following file layout must be present after installation:

```
<KSP_ROOT>
	[GameData]
		[TweakScale]
			[Plugins]
				KSPe.Light.TweakScale.dll
				Scale.dll
			[patches]
				...
			CHANGE_LOG.md
			DefaultScales.cfg
			Examples.cfg
			LICENSE
			NOTICE
			README.md
			ScaleExponents.cfg
			TweakScale.version
			documentation.txt
		[...]
		[TweakScaleCompanion]
			[...]
			[Legacy]
				CHANGE_LOG.md
				LICENSE*
				NOTICE
				README.md
				[patches]
					...
		ModuleManager.dll
		...
	KSP.log
	PartDatabase.cfg
	...
```


### Dependencies

* TweakScale /L 2.4.5 or later
	+ **NOT** included
* Optionals (**not included**)
	+ Modular Fuel Tanks
* Module Manager 3.1.3 or later
	+ **NOT** included
