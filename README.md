(Ai will spawn in events like police, heli crashes, and will spawn in or around city and village police stations ! ) Copy and Paste this in AI Patrol Settings:
{
    "m_Version": 11,
    "Enabled": 1,
    "DespawnTime": 600.0,
    "RespawnTime": -1.0,
    "MinDistRadius": 400.0,
    "MaxDistRadius": 1000.0,
    "DespawnRadius": 1100.0,
    "AccuracyMin": -1.0,
    "AccuracyMax": -1.0,
    "ThreatDistanceLimit": -1.0,
    "DamageMultiplier": -1.0,
    "ObjectPatrols": [
        {
	    "Faction": "Mercenaries",
            "Formation": "",
            "LoadoutFile": "TTSKOLoadout",
            "NumberOfAI": -2,
            "Behaviour": "HALT_OR_ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 5.0,
            "MaxSpreadRadius": 20.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "ClassName": "Land_Village_PoliceStation"
        },
        {
	    "Faction": "Mercenaries",
            "Formation": "",
            "LoadoutFile": "TTSKOLoadout",
            "NumberOfAI": -2,
            "Behaviour": "HALT_OR_ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 5.0,
            "MaxSpreadRadius": 20.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "ClassName": "Land_City_PoliceStation"
        },
        {
            "Faction": "West",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": -3,
            "Behaviour": "HALT_OR_ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 5.0,
            "MaxSpreadRadius": 20.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "ClassName": "Wreck_UH1Y"
        },
        {
            "Faction": "East",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": -3,
            "Behaviour": "HALT_OR_ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 5.0,
            "MaxSpreadRadius": 20.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "ClassName": "Wreck_Mi8_Crashed"
        },
        {
            "Faction": "East",
            "Formation": "",
            "LoadoutFile": "PoliceLoadout",
            "NumberOfAI": -3,
            "Behaviour": "HALT_OR_ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 5.0,
            "MaxSpreadRadius": 20.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "ClassName": "Land_Wreck_sed01_aban1_police"
        },
        {
            "Faction": "East",
            "Formation": "",
            "LoadoutFile": "PoliceLoadout",
            "NumberOfAI": -3,
            "Behaviour": "HALT_OR_ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 5.0,
            "MaxSpreadRadius": 20.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "ClassName": "Land_Wreck_sed01_aban2_police"
        },
        {
            "Faction": "West",
            "Formation": "",
            "LoadoutFile": "NBCLoadout",
            "NumberOfAI": -3,
            "Behaviour": "HALT_OR_ALTERNATE",
            "Speed": "JOG",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 0.0,
            "MaxSpreadRadius": 150.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "ClassName": "ContaminatedArea_Static"
        },
        {
            "Faction": "West",
            "Formation": "",
            "LoadoutFile": "NBCLoadout",
            "NumberOfAI": -3,
            "Behaviour": "HALT_OR_ALTERNATE",
            "Speed": "JOG",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 0.0,
            "MaxSpreadRadius": 150.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "ClassName": "ContaminatedArea_Dynamic"
        }
    ],
    "Patrols": [ 
 {
            "Faction": "Mercenaries",
			"Formation": "",
            "LoadoutFile": "TTSKOLoadout",
            "NumberOfAI": 3,
            "Behaviour": "HALT",
            "Speed": "WALK",
            "UnderThreatSpeed": "WALK",
            "CanBeLooted": 1,
            "UnlimitedReload": 1,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 10.0,
            "Chance": 1.0,
			"WaypointInterpolation": "",
            "RespawnTime": -2.0,
            "Waypoints": [
                [
                    2664.947509765625,
                126.82585144042969,
                3015.818603515625
                ]
            ]
        },
		
		{
            "Faction": "Mercenaries",
			"Formation": "",
            "LoadoutFile": "TTSKOLoadout",
            "NumberOfAI": 3,
            "Behaviour": "HALT",
            "Speed": "WALK",
            "UnderThreatSpeed": "WALK",
            "CanBeLooted": 1,
            "UnlimitedReload": 1,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 10.0,
            "Chance": 1.0,
			"WaypointInterpolation": "",
            "RespawnTime": -2.0,
            "Waypoints": [
                [
                    3844.716064453125,
                234.93653869628907,
                4786.36376953125
                ]
            ]
        },
	
	{
            "Faction": "Mercenaries",
			"Formation": "",
            "LoadoutFile": "TTSKOLoadout",
            "NumberOfAI": 3,
            "Behaviour": "HALT",
            "Speed": "WALK",
            "UnderThreatSpeed": "WALK",
            "CanBeLooted": 1,
            "UnlimitedReload": 1,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 10.0,
            "Chance": 1.0,
			"WaypointInterpolation": "",
            "RespawnTime": -2.0,
            "Waypoints": [
                [
                     10249.591796875,
                26.494564056396486,
                3188.3017578125
                ]
            ]
        },
	
	{
            "Faction": "Mercenaries",
			"Formation": "",
            "LoadoutFile": "TTSKOLoadout",
            "NumberOfAI": 3,
            "Behaviour": "HALT",
            "Speed": "WALK",
            "UnderThreatSpeed": "WALK",
            "CanBeLooted": 1,
            "UnlimitedReload": 1,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 10.0,
            "Chance": 1.0,
			"WaypointInterpolation": "",
            "RespawnTime": -2.0,
            "Waypoints": [
                [
                    10074.37890625,
                257.09033203125,
                8863.6650390625
                ]
            ]
        },
	
	{
            "Faction": "Mercenaries",
			"Formation": "",
            "LoadoutFile": "TTSKOLoadout",
            "NumberOfAI": 3,
            "Behaviour": "HALT",
            "Speed": "WALK",
            "UnderThreatSpeed": "WALK",
            "CanBeLooted": 1,
            "UnlimitedReload": 1,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 10.0,
            "Chance": 1.0,
			"WaypointInterpolation": "",
            "RespawnTime": -2.0,
            "Waypoints": [
                [
                    7095.17724609375,
                255.92236328125,
                6480.31787109375
                ]
            ]
        },
	
	{
            "Faction": "Mercenaries",
			"Formation": "",
            "LoadoutFile": "TTSKOLoadout",
            "NumberOfAI": 3,
            "Behaviour": "HALT",
            "Speed": "WALK",
            "UnderThreatSpeed": "WALK",
            "CanBeLooted": 1,
            "UnlimitedReload": 1,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 10.0,
            "Chance": 1.0,
			"WaypointInterpolation": "",
            "RespawnTime": -2.0,
            "Waypoints": [
                [
                     6633.8271484375,
                139.1641845703125,
                12715.4384765625
                ]
            ]
        },
		
		{
            "Faction": "Mercenaries",
			"Formation": "",
            "LoadoutFile": "TTSKOLoadout",
            "NumberOfAI": 3,
            "Behaviour": "HALT",
            "Speed": "WALK",
            "UnderThreatSpeed": "WALK",
            "CanBeLooted": 1,
            "UnlimitedReload": 1,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 10.0,
            "Chance": 1.0,
			"WaypointInterpolation": "",
            "RespawnTime": -2.0,
            "Waypoints": [
                [
                 2356.59228515625,
                367.9375915527344,
                14129.271484375
                ]
            ]
        },
        { 
            "Faction": "West",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 3,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    4211.22265625,
                    109.02338409423828,
                    6382.064453125
                ],
                [
                    4151.66259765625,
                    105.45065307617188,
                    6080.29443359375
                ],
                [
                    4160.9716796875,
                    105.41259765625,
                    6035.10302734375
                ],
                [
                    4160.69921875,
                    106.25148010253906,
                    5906.830078125
                ],
                [
                    4107.86279296875,
                    108.93052673339844,
                    5898.48291015625
                ],
                [
                    4057.258056640625,
                    114.17473602294922,
                    5584.595703125
                ],
                [
                    4084.56005859375,
                    113.232421875,
                    5494.5400390625
                ],
                [
                    4079.30810546875,
                    113.80116271972656,
                    5435.953125
                ],
                [
                    4081.73583984375,
                    113.40250396728516,
                    5385.576171875
                ],
                [
                    4067.26611328125,
                    109.78838348388672,
                    4904.5087890625
                ],
                [
                    4126.5048828125,
                    107.37117767333985,
                    4647.12890625
                ]
            ]
        },
        {
            "Faction": "West",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 3,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    4508.8603515625,
                    109.34727478027344,
                    6230.75146484375
                ],
                [
                    4448.49072265625,
                    109.37779235839844,
                    6025.892578125
                ],
                [
                    4546.90283203125,
                    112.05754852294922,
                    6126.59033203125
                ],
                [
                    4613.9755859375,
                    110.16388702392578,
                    6112.86962890625
                ],
                [
                    4563.82568359375,
                    110.69610595703125,
                    5797.4501953125
                ],
                [
                    4551.8056640625,
                    110.55508422851563,
                    5652.876953125
                ],
                [
                    4312.20361328125,
                    110.75215148925781,
                    5366.94189453125
                ]
            ]
        },
        {
            "Faction": "Raiders",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 1,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    10545.6875,
                    38.03715515136719,
                    10384.205078125
                ],
                [
                    10502.615234375,
                    40.37776184082031,
                    10464.7548828125
                ],
                [
                    10700.634765625,
                    34.34654235839844,
                    10461.470703125
                ],
                [
                    10645.3505859375,
                    36.45183563232422,
                    10377.76953125
                ]
            ]
        },
        {
            "Faction": "Raiders",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 1,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    8588.2099609375,
                    103.30472564697266,
                    13439.0029296875
                ],
                [
                    8578.5859375,
                    106.48522186279297,
                    13465.28125
                ],
                [
                    8605.7177734375,
                    112.45527648925781,
                    13521.6259765625
                ],
                [
                    8640.509765625,
                    120.11822509765625,
                    13590.3603515625
                ],
                [
                    8641.9765625,
                    127.32777404785156,
                    13644.0693359375
                ],
                [
                    8643.5234375,
                    123.58162689208985,
                    13609.8486328125
                ],
                [
                    8724.0771484375,
                    121.00849914550781,
                    13532.3525390625
                ],
                [
                    8792.484375,
                    119.34481048583985,
                    13479.8671875
                ],
                [
                    8843.3583984375,
                    122.08585357666016,
                    13469.46484375
                ],
                [
                    8881.1611328125,
                    121.29359436035156,
                    13413.06640625
                ],
                [
                    8837.0048828125,
                    121.07237243652344,
                    13470.0068359375
                ],
                [
                    8742.0390625,
                    121.24681091308594,
                    13516.587890625
                ],
                [
                    8704.23828125,
                    119.76278686523438,
                    13546.5166015625
                ],
                [
                    8609.14453125,
                    113.18451690673828,
                    13527.6015625
                ],
                [
                    8573.0166015625,
                    112.24705505371094,
                    13530.662109375
                ],
                [
                    8563.083984375,
                    118.17390441894531,
                    13576.212890625
                ],
                [
                    8500.525390625,
                    135.5902099609375,
                    13653.76953125
                ],
                [
                    8456.375,
                    139.3658447265625,
                    13677.1279296875
                ],
                [
                    8546.6103515625,
                    126.12944030761719,
                    13615.544921875
                ],
                [
                    8566.7470703125,
                    116.35537719726563,
                    13563.6884765625
                ],
                [
                    8573.123046875,
                    112.56271362304688,
                    13532.7392578125
                ],
                [
                    8563.7001953125,
                    107.29808807373047,
                    13476.4658203125
                ],
                [
                    8586.0478515625,
                    103.66409301757813,
                    13442.435546875
                ]
            ]
        },
        {
            "Faction": "Civilian",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 4,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    7841.3349609375,
                    76.69611358642578,
                    105.50646209716797
                ],
                [
                    7874.43359375,
                    86.5004653930664,
                    194.1827392578125
                ],
                [
                    7881.091796875,
                    88.8189468383789,
                    247.87342834472657
                ],
                [
                    7804.40625,
                    88.37928009033203,
                    365.87762451171877
                ],
                [
                    7792.43017578125,
                    88.65029907226563,
                    383.00140380859377
                ],
                [
                    7762.8076171875,
                    83.7376708984375,
                    334.8746337890625
                ],
                [
                    7760.65380859375,
                    84.683837890625,
                    353.2117919921875
                ],
                [
                    7768.95703125,
                    88.44590759277344,
                    421.0120544433594
                ],
                [
                    7781.3388671875,
                    89.11323547363281,
                    430.4404296875
                ],
                [
                    7769.263671875,
                    90.8582534790039,
                    472.48828125
                ],
                [
                    7776.35693359375,
                    91.00643920898438,
                    493.6338195800781
                ],
                [
                    7762.3740234375,
                    91.01448822021485,
                    534.7476806640625
                ],
                [
                    7739.28076171875,
                    91.13427734375,
                    564.8483276367188
                ],
                [
                    7639.0,
                    120.3280258178711,
                    769.7715454101563
                ],
                [
                    7378.47998046875,
                    94.51292419433594,
                    764.41748046875
                ],
                [
                    7325.0390625,
                    93.79295349121094,
                    820.4214477539063
                ],
                [
                    7323.55419921875,
                    95.07601928710938,
                    869.6690673828125
                ],
                [
                    6920.2666015625,
                    84.64220428466797,
                    926.835693359375
                ],
                [
                    6942.748046875,
                    84.11299133300781,
                    977.515380859375
                ],
                [
                    6901.28759765625,
                    82.87837982177735,
                    1002.5807495117188
                ],
                [
                    6848.884765625,
                    91.49227142333985,
                    967.189453125
                ],
                [
                    6835.8408203125,
                    84.59558868408203,
                    942.7606201171875
                ],
                [
                    6655.30908203125,
                    92.31884765625,
                    793.1343383789063
                ],
                [
                    6639.6552734375,
                    91.83074188232422,
                    792.5340576171875
                ],
                [
                    6635.73095703125,
                    92.24980163574219,
                    780.7630004882813
                ]
            ]
        },
        {
            "Faction": "Civilian",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 4,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    9963.3466796875,
                    55.640098571777347,
                    10900.8447265625
                ],
                [
                    9965.3984375,
                    54.729034423828128,
                    10969.5361328125
                ],
                [
                    9924.380859375,
                    57.23215103149414,
                    10901.9677734375
                ]
            ]
        },
        {
            "Faction": "West",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 4,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    8796.83984375,
                    59.87810134887695,
                    2547.0
                ],
                [
                    8745.0,
                    59.13669967651367,
                    2523.199951171875
                ],
                [
                    8710.4404296875,
                    57.56959915161133,
                    2499.0
                ],
                [
                    8794.23046875,
                    55.971900939941409,
                    2417.0
                ],
                [
                    8756.990234375,
                    55.852901458740237,
                    2370.0
                ],
                [
                    8782.759765625,
                    56.19160079956055,
                    2345.0
                ],
                [
                    8740.169921875,
                    56.16619873046875,
                    2304.0
                ],
                [
                    8751.150390625,
                    56.12160110473633,
                    2284.0
                ],
                [
                    8828.4697265625,
                    56.64950180053711,
                    2234.0
                ],
                [
                    8764.01953125,
                    53.292198181152347,
                    2139.0
                ],
                [
                    8656.01953125,
                    47.42570114135742,
                    2009.0
                ]
            ]
        },
        {
            "Faction": "East",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 4,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    1583.5799560546876,
                    292.8039855957031,
                    2961.0
                ],
                [
                    1600.8399658203126,
                    294.2919921875,
                    3006.0
                ],
                [
                    1631.43994140625,
                    295.4079895019531,
                    3029.0
                ],
                [
                    1652.8900146484376,
                    297.989990234375,
                    3079.60009765625
                ],
                [
                    1685.6300048828126,
                    297.55499267578127,
                    3080.0
                ]
            ]
        },
        {
            "Faction": "East",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 4,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    1824.93994140625,
                    294.0660095214844,
                    3075.0
                ],
                [
                    1884.949951171875,
                    293.22198486328127,
                    3047.0
                ],
                [
                    1846.68994140625,
                    289.88800048828127,
                    2996.0
                ],
                [
                    1812.780029296875,
                    290.3330078125,
                    3001.0
                ],
                [
                    1796.6500244140626,
                    287.9750061035156,
                    2990.0
                ]
            ]
        },
        {
            "Faction": "West",
            "Formation": "",
            "LoadoutFile": "",
            "NumberOfAI": 4,
            "Behaviour": "ALTERNATE",
            "Speed": "WALK",
            "UnderThreatSpeed": "SPRINT",
            "CanBeLooted": 1,
            "UnlimitedReload": 0,
            "AccuracyMin": -1.0,
            "AccuracyMax": -1.0,
            "ThreatDistanceLimit": -1.0,
            "DamageMultiplier": -1.0,
            "MinDistRadius": -2.0,
            "MaxDistRadius": -2.0,
            "DespawnRadius": -2.200000047683716,
            "MinSpreadRadius": 1.0,
            "MaxSpreadRadius": 100.0,
            "Chance": 1.0,
            "WaypointInterpolation": "",
            "DespawnTime": -1.0,
            "RespawnTime": -2.0,
            "UseRandomWaypointAsStartPoint": 1,
            "Waypoints": [
                [
                    7160.85009765625,
                    84.55609893798828,
                    585.60400390625
                ],
                [
                    6677.509765625,
                    95.07990264892578,
                    770.1129760742188
                ]
            ]
        }
    ]
}
