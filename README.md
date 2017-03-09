## BaseMarkers_ExAd
# Installation
0. Add BaseMarker folder to your ExAd XM8 Apps folder; Exile.Mission > ExAdClient > XM8 > Apps > Place_Folder

0. Open your config.cpp file
0. Locate class CfgXM8
0. Add "BaseMarker" to the extraApps line
0. Add the folowing line in the CfgXM8 class:
```
	class BaseMarker 
	{
		controlID = 50500;
		title = "Base Marker";		
		logo = "ExAdClient\XM8\Apps\BaseMarker\BaseMarker.paa";
		onLoad = "ExAdClient\XM8\Apps\BaseMarker\onLoad.sqf";
	};
```

You're Done! Enjoy.
