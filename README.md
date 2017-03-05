# BaseMarkers_ExAd
BaseMarkers_ExAd

# Installation
1. Add BaseMarker folder to your ExAd XM8 Apps folder; Exile.Mission > ExAdClient > XM8 > Apps > Place_Folder

2. Open your config.cpp file
3. Locate class CfgXM8
4. Add "BaseMarker" to the extraApps line
5. Add the folowing line in the CfgXM8 class:

	class BaseMarker 
	{
		controlID = 50500;
		title = "Base Marker";
		logo = "CP\ExAdClient\XM8\Apps\BaseMarker\BaseMarker.paa";
		onLoad = "CP\ExAdClient\XM8\Apps\BaseMarker\onLoad.sqf";
	};

6. You're Done!
