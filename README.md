Cherno-Train-Service
=====================

Train service from Berezino - Kamenka =)

Train starts at Berezino, travels down the coast all the way to Kamenka.
It stops at every train station along the way. Sounds the horn at every level crossing.

Add the files to mp mission folder under scripts.

Add this to the mission.sqm file

	class Vehicles
	{
		items=1;
		class Item0
		{
			position[]={13113.642,6.0146008,10507.089};
			azimut=199.69299;
			id=1;
			side="EMPTY";
			vehicle="Land_loco_742_blue";
			skill=0.60000002;
			init="_nil = [this,1] execVM ""scripts\Train\Train_Start.sqf"";";
		};
	};
	
Might have to add some battleye filters.
