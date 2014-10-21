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

Just change the location here ^^up there if you put it into a different folder.

Might have to add some battleye filters.

Add this to description.ext

class CfgSounds
{
    sounds[] = {};

    class NoSound
    {
    name = "NoSound";
        sound[] = {"", 0, 1};
        titles[] = {};
    };

#include "scripts\Train\sounds.hpp"


I would like to thank Zonekiller for the orginal files =)
Script by Zonekiller  -- http://zonekiller.ath.cx --    -- zonekiller@live.com.au --
http://www.armaholic.com/page.php?id=16784
