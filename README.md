# BaseMarkers_ExAd
BaseMarkers_ExAd

# Installation

Add BaseMarker folder to your ExAd XM8 Apps folder
Exile.Mission > ExAdClient > XM8 > Apps > Place_Folder

Open your config.cpp file
Locate class CfgXM8
Add "BaseMarker" to the extraApps line
Add the folowing line in the CfgXM8 class

	class BaseMarker 
	{
		controlID = 50500;
		title = "Base Marker";		
		logo = "CP\ExAdClient\XM8\Apps\BaseMarker\BaseMarker.paa";
		onLoad = "CP\ExAdClient\XM8\Apps\BaseMarker\onLoad.sqf";
	};

You're Done!
