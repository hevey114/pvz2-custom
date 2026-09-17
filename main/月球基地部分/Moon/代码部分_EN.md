> **⚠️ AI-Translated document**
> This file is an **AI-generated English translation** of the original Chinese file “Moon/代码部分.md” (by the same author). It is provided for convenience only; please treat the original Chinese as authoritative. Code/IDs in “code” documents are kept untouched.
>
> _这份文档是对原中文《Moon/代码部分.md》的 AI 英译版，仅供参考，内容以原文为准。_

## LevelModules code
{
			"objclass": "StageModuleProperties",
			"aliases": [
				"MoonStage"
			],
			"objdata": {
				"ResourceGroupNames": [
					"DelayLoad_Background_Moon",
					"Dirt_Spawn_Future",
					"AudioModern"
				],
				"GroupsToUnloadForAds": [
					"DelayLoad_Background_Moon"
				],
				"StagePrefix": "modern",
				"BackgroundResourceGroup": "DelayLoad_Background_Moon",
				"BackgroundImagePrefix": "IMAGE_BACKGROUNDS_MOON",
				"LevelPowerupSet": "LevelPowerupsDefault",
				"BasicZombieTypeName": "moon",
				"FlagZombieTypeName": "moon_flag",
				"Armor1ZombieTypeName": "moon_armor1",
				"Armor2ZombieTypeName": "moon_armor2",
				"RailcartDefaultTypeName": "railcart_tutorial",
				"GravestoneDefaultTypeName": "moon_ore",
				"DirtSpawnEffectName": "POPANIM_EFFECTS_DIRT_SPAWN_FUTURE",
				"MusicSuffix": "Moon",
				"DisabledStreetCells": [
					{
						"mX": 0,
						"mY": 0
					},
					{
						"mX": 0,
						"mY": 1
					},
					{
						"mX": 0,
						"mY": 2
					},
					{
						"mX": 0,
						"mY": 3
					},
					{
						"mX": 0,
						"mY": 4
					},
					{
						"mX": 0,
						"mY": 5
					},
					{
						"mX": 0,
						"mY": 6
					},
					{
						"mX": 0,
						"mY": 7
					},
					{
						"mX": 0,
						"mY": 8
					},
					{
						"mX": 0,
						"mY": 9
					},
					{
						"mX": 1,
						"mY": 0
					},
					{
						"mX": 1,
						"mY": 1
					},
					{
						"mX": 1,
						"mY": 2
					},
					{
						"mX": 1,
						"mY": 3
					},
					{
						"mX": 1,
						"mY": 4
					},
					{
						"mX": 1,
						"mY": 5
					},
					{
						"mX": 1,
						"mY": 6
					},
					{
						"mX": 1,
						"mY": 7
					},
					{
						"mX": 1,
						"mY": 8
					},
					{
						"mX": 1,
						"mY": 9
					},
					{
						"mX": 2,
						"mY": 0
					},
					{
						"mX": 2,
						"mY": 1
					},
					{
						"mX": 2,
						"mY": 2
					},
					{
						"mX": 2,
						"mY": 3
					},
					{
						"mX": 2,
						"mY": 4
					},
					{
						"mX": 2,
						"mY": 5
					},
					{
						"mX": 2,
						"mY": 6
					},
					{
						"mX": 2,
						"mY": 7
					},
					{
						"mX": 2,
						"mY": 8
					},
					{
						"mX": 2,
						"mY": 9
					},
					{
						"mX": 5,
						"mY": 9
					},
					{
						"mX": 6,
						"mY": 0
					},
					{
						"mX": 6,
						"mY": 1
					},
					{
						"mX": 6,
						"mY": 2
					},
					{
						"mX": 6,
						"mY": 3
					},
					{
						"mX": 6,
						"mY": 4
					},
					{
						"mX": 6,
						"mY": 5
					},
					{
						"mX": 6,
						"mY": 6
					},
					{
						"mX": 6,
						"mY": 7
					},
					{
						"mX": 6,
						"mY": 8
					},
					{
						"mX": 6,
						"mY": 9
					},
					{
						"mX": 7,
						"mY": 0
					},
					{
						"mX": 7,
						"mY": 6
					},
					{
						"mX": 7,
						"mY": 7
					},
					{
						"mX": 7,
						"mY": 8
					},
					{
						"mX": 7,
						"mY": 9
					},
					{
						"mX": 8,
						"mY": 0
					},
					{
						"mX": 8,
						"mY": 6
					},
					{
						"mX": 8,
						"mY": 7
					},
					{
						"mX": 8,
						"mY": 8
					},
					{
						"mX": 8,
						"mY": 9
					}
				]
			}
		},
		{
			"objclass": "LawnMowerProperties",
			"aliases": [
				"MoonMowers"
			],
			"objdata": {
				"ResourceGroupNames": [
					"MoonMowerGroup"
				],
				"MowerEntryAnimDuration": 2.500000,
				"MowerActivatedAudioEvent": "Play_UI_Game_Mower_Modern_TurnOn",
				"MowerPopAnim": "POPANIM_MOWERS_MOWER_MOON",
				"UnlimitedMowers": false
			}
		},
		{
            "comment":"Moon Floor",
			"aliases": [
				"MoonGroundUI"
			],
			"objclass": "InitialGridItemProperties",
			"objdata": {
				"InitialGridItemPlacements": [
					{
						"GridX": 0,
						"GridY": 0,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 1,
						"GridY": 0,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 2,
						"GridY": 0,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 3,
						"GridY": 0,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 4,
						"GridY": 0,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 5,
						"GridY": 0,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 6,
						"GridY": 0,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 7,
						"GridY": 0,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 8,
						"GridY": 0,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 0,
						"GridY": 1,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 1,
						"GridY": 1,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 2,
						"GridY": 1,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 3,
						"GridY": 1,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 4,
						"GridY": 1,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 5,
						"GridY": 1,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 6,
						"GridY": 1,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 7,
						"GridY": 1,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 8,
						"GridY": 1,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 0,
						"GridY": 2,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 1,
						"GridY": 2,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 2,
						"GridY": 2,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 3,
						"GridY": 2,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 4,
						"GridY": 2,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 5,
						"GridY": 2,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 6,
						"GridY": 2,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 7,
						"GridY": 2,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 8,
						"GridY": 2,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 0,
						"GridY": 3,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 1,
						"GridY": 3,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 2,
						"GridY": 3,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 3,
						"GridY": 3,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 4,
						"GridY": 3,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 5,
						"GridY": 3,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 6,
						"GridY": 3,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 7,
						"GridY": 3,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 8,
						"GridY": 3,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 0,
						"GridY": 4,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 1,
						"GridY": 4,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 2,
						"GridY": 4,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 3,
						"GridY": 4,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 4,
						"GridY": 4,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 5,
						"GridY": 4,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 6,
						"GridY": 4,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 7,
						"GridY": 4,
						"TypeName": "moon_ground"
					},
					{
						"GridX": 8,
						"GridY": 4,
						"TypeName": "moon_ground"
					}
				]
			}
		}

## GridItemTypes code (Moon Floor — a floor every plant can be planted on; Power Crystal (gives sun); and the rocket's tool floor that blocks planting)
        {
			"objclass": "GridItemType",
			"aliases": [
				"moon_ground"
			],
			"objdata": {
				"TypeName": "moon_ground",
				"GridItemClass": "GridItemZombiePortal",
				"Properties": "RTID(MoonGroundDefault@GridItemProps)",
				"ResourceGroups": [
					"PlantLavaGuava"
				]
			}
		},
		{
			"objclass": "GridItemType",
			"aliases": [
				"moon_all_ground"
			],
			"objdata": {
				"TypeName": "moon_all_ground",
				"GridItemClass": "GridItemZombiePortal",
				"Properties": "RTID(MoonGroundAllDefault@GridItemProps)",
				"ResourceGroups": [
					"PlantLavaGuava"
				]
			}
		},
		{
			"objclass": "GridItemType",
			"aliases": [
				"moon_ore"
			],
			"objdata": {
				"TypeName": "moon_ore",
				"GridItemClass": "GridItemGravestoneSunOnDestruction",
				"ResourceGroups": [
					"MoonOre",
					"Tombstone_Dark_Effects"
				],
				"Properties": "RTID(MoonOreDefault@GridItemProps)"
			}
		},
		{
			"objclass": "GridItemType",
			"aliases": [
				"moon_rocket_ground"
			],
			"objdata": {
				"TypeName": "moon_rocket_ground",
				"GridItemClass": "GridItemZombiePortal",
				"Properties": "RTID(MoonGroundProp@GridItemProps)",
				"ResourceGroups": [
					"PlantLavaGuava"
				]
			}
		}

## GridItemProps code
        {
			"aliases": [
				"MoonGroundDefault"
			],
			"objclass": "GridItemZombiePortalProps",
			"objdata": {
				"CanBeMowed": false,
				"CloseAnimation": "end",
				"Height": "ground",
				"Hitpoints": 10000000,
				"PopAnim": "POPANIM_EFFECTS_LAVAGUAVA_LAVA_MOON",
				"PopAnimRenderOffset": {
					"x": 9999,
					"y": 125
				},
				"TimeBetweenSpawns": {
					"Max": 0.350000,
					"Min": 0.350000
				},
				"PopAnimRigClass": "GridItemZombiePortal_AnimRig",
				"PlantingRestrictions": {
					"BlockedPlantingReason": "PLANTING_NOT_ON_CRATERS",
					"List": [
						"cosmos",
						"cosmos_ground",
						"cosmicnut",
						"cosmicnut_transform",
						"cosmictallnut",
						"cosmictallnut_transform",
						"cosmicpea_intro",
						"cosmicpea",
						"cosmicrepeater_intro",
						"cosmicrepeater",
						"cosmicgatling_intro",
						"cosmicgatling",
						"cosmicpuffshroom",
						"cosmicpuffshroom_normal",
						"cosmicscaredyshroom",
						"cosmicscaredyshroom_normal",
						"cosmicfumeshroom",
						"cosmicfumeshroom_normal",
						"shooting_starfruit_new_intro",
						"shooting_starfruit_new",
						"pecanolith",
						"onionrings",
						"pineclone_intro",
						"pineclone",
						"pineclone_clone_intro",
						"pineclone_clone"
					],
					"ListType": "includelist"
				},
				"SpawnAnimation": "spawn",
				"World": "",
				"ZombiesToSpawn": 0,
				"ZombieSpawnPointOffset": -18,
				"ZombieTypesToSpawn": [
					{
						"Weight": 1,
						"ZombieTypeName": "dummy2"
					}
				]
			}
		},
		{
			"aliases": [
				"MoonGroundAllDefault"
			],
			"objclass": "GridItemZombiePortalProps",
			"objdata": {
				"CanBeMowed": false,
				"CloseAnimation": "end",
				"Height": "ground",
				"Hitpoints": 10000000,
				"PopAnim": "POPANIM_EFFECTS_LAVAGUAVA_LAVA_MOON",
				"PopAnimRenderOffset": {
					"x": 9999,
					"y": 125
				},
				"TimeBetweenSpawns": {
					"Max": 0.350000,
					"Min": 0.350000
				},
				"PopAnimRigClass": "GridItemZombiePortal_AnimRig",
				"PlantingRestrictions": {
					"BlockedPlantingReason": "PLANTING_NOT_ON_CRATERS",
					"List": [],
					"ListType": "excludelist"
				},
				"SpawnAnimation": "spawn",
				"World": "",
				"ZombiesToSpawn": 0,
				"ZombieSpawnPointOffset": -18,
				"ZombieTypesToSpawn": [
					{
						"Weight": 1,
						"ZombieTypeName": "dummy2"
					}
				]
			}
		},
		{
			"aliases": [
				"MoonOreDefault"
			],
			"objclass": "GridItemGravestoneSunOnDestructionPropertySheet",
			"objdata": {
				"AmountToSpawn": 50,
				"ArtCenter": {
					"x": 98,
					"y": 127
				},
				"BreakEffect": "POPANIM_SUNORE_MOON_BREAK",
				"BreakEffectSound": "Play_Zomb_Egypt_Grave_Crumble",
				"DamageStateCount": 2,
				"HitRectOffsetWidth": -30,
				"HitRectOffsetX": 15,
				"Hitpoints": 500,
				"PopAnim": "POPANIM_SUNORE_MOON",
				"ScaledProps": [
					{
						"Arg1": 1.300000,
						"Arg2": 0.050000,
						"Formula": "standard",
						"Key": "Hitpoints"
					}
				]
			}
		},
		{
			"aliases": [
				"MoonGroundProp"
			],
			"objclass": "GridItemZombiePortalProps",
			"objdata": {
				"CanBeMowed": false,
				"CloseAnimation": "end",
				"Height": "ground",
				"Hitpoints": 10000000,
				"PopAnim": "POPANIM_EFFECTS_LAVAGUAVA_LAVA",
				"PopAnimRenderOffset": {
					"x": 9999,
					"y": 125
				},
				"TimeBetweenSpawns": {
					"Max": 0.350000,
					"Min": 0.350000
				},
				"PopAnimRigClass": "GridItemZombiePortal_AnimRig",
				"PlantingRestrictions": {
					"BlockedPlantingReason": "PLANTING_NOT_ON_CRATERS",
					"List": [],
					"ListType": "includelist"
				},
				"SpawnAnimation": "spawn",
				"World": "",
				"ZombiesToSpawn": 0,
				"ZombieSpawnPointOffset": -18,
				"ZombieTypesToSpawn": [
					{
						"Weight": 1,
						"ZombieTypeName": "dummy2"
					}
				]
			}
		}

## ZombieTypes code
        {
			"#comment": "################################## Moon Rocket (not a zombie — a turret mechanic like the one in Crimson Front; don't spawn it directly) #####################################"
		},
		{
			"#": "for visuals and attacking",
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket"
			],
			"objdata": {
				"#comment": "Main entity — place this one in the level",
				"TypeName": "moon_rocket",
				"ZombieClass": "ZombieGeneralTreadmill",
				"Properties": "RTID(ZombieMoonRocket@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_GeneralTreadmill",
				"PopAnim": "POPANIM_MOON_ROCKET_DUAL",
				"HomeWorld": "moon",
				"FlagType": "flag_normal",
				"Placeable": true
			}
		},
		{
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket_visual_initial"
			],
			"objdata": {
				"#comment": "Visual body — the thing you see",
				"TypeName": "moon_rocket_visual_initial",
				"ZombieClass": "ZombieGeneralTreadmill",
				"Properties": "RTID(ZombieMoonRocketVisualInitial@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_GeneralTreadmill",
				"PopAnim": "POPANIM_MOON_ROCKET_DUAL",
				"HastyOnStart": false,
				"HomeWorld": "moon",
				"Placeable": true
			}
		},
		{
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket_plantfire_initial"
			],
			"objdata": {
				"#comment": "Plant-side judge — gets hit by plants",
				"TypeName": "moon_rocket_plantfire_initial",
				"ZombieClass": "ZombieGeneralZmech",
				"Properties": "RTID(ZombieMoonRocketPlantFireInitial@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_GeneralTreadmill",
				"PopAnim": "POPANIM_MOON_ROCKET_DUAL",
				"HomeWorld": "moon",
				"Placeable": true
			}
		},
		{
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket_zombiefire_initial"
			],
			"objdata": {
				"#comment": "Zombie-side judge — gets chewed on by zombies",
				"TypeName": "moon_rocket_zombiefire_initial",
				"ZombieClass": "ZombieGeneralZmech",
				"Properties": "RTID(ZombieMoonRocketZombieFireInitial@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_GeneralTreadmill",
				"PopAnim": "POPANIM_MOON_ROCKET_DUAL",
				"HomeWorld": "moon",
				"Placeable": true
			}
		},
		{
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket_visual_fire_plant"
			],
			"objdata": {
				"#comment": "Plant wins: fires the projectile and blows things up to the right",
				"TypeName": "moon_rocket_visual_fire_plant",
				"ZombieClass": "ZombieGeneralTreadmill",
				"Properties": "RTID(ZombieMoonRocketVisualFirePlant@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_GeneralTreadmill",
				"PopAnim": "POPANIM_MOON_ROCKET_DUAL",
				"HastyOnStart": false,
				"HomeWorld": "moon",
				"Placeable": true
			}
		},
		{
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket_visual_fire_zombie"
			],
			"objdata": {
				"#comment": "Zombie wins: blows up the plants",
				"TypeName": "moon_rocket_visual_fire_zombie",
				"ZombieClass": "ZombieGeneralTreadmill",
				"Properties": "RTID(ZombieMoonRocketVisualFireZombie@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_GeneralTreadmill",
				"PopAnim": "POPANIM_MOON_ROCKET_DUAL",
				"HastyOnStart": false,
				"HomeWorld": "moon",
				"Placeable": true
			}
		},
		{
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket_endlevel_wait"
			],
			"objdata": {
				"#comment": "Used to settle / end the level",
				"TypeName": "moon_rocket_endlevel_wait",
				"ZombieClass": "ZombieGeneralTreadmill",
				"Properties": "RTID(ZombieMoonRocketVisualEndLevelWait@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_GeneralTreadmill",
				"PopAnim": "POPANIM_ZOMBIE_ZOMBIE_DUMMY",
				"HastyOnStart": false,
				"HomeWorld": "moon",
				"Placeable": true
			}
		},
		{
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket_crosshair"
			],
			"objdata": {
				"#comment": "Landing-zone warning marker",
				"TypeName": "moon_rocket_crosshair",
				"ZombieClass": "ZombieGeneralTreadmill",
				"Properties": "RTID(ZombieMoonRocketCrosshair@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_GeneralTreadmill",
				"PopAnim": "POPANIM_MOON_ROCKET_CROSSHAIR",
				"HastyOnStart": true,
				"HomeWorld": "moon",
				"Placeable": true
			}
		},
		{
			"#comment": "Moon Rocket intro — used when a rocket lands inside the level. You must customise the intro part in the level to decide how many land; spawning it directly crashes, because I attached a @CurrentLevel"
		},
		{
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket_intro"
			],
			"objdata": {
				"TypeName": "moon_rocket_intro",
				"ZombieClass": "ZombieGeneralTreadmill",
				"Properties": "RTID(MoonRocketIntroDefault@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_GeneralCaesar",
				"PopAnim": "POPANIM_ZOMBIE_ZOMBIE_DUMMY",
				"HomeWorld": "moon",
				"Placeable": true,
				"FlagType":"flag_normal",
				"HastyOnStart": false,
				"IsBasicZombie": false
			}
		},
		{
			"objclass": "ZombieType",
			"aliases": [
				"moon_rocket_intro_anim"
			],
			"objdata": {
				"TypeName": "moon_rocket_intro_anim",
				"ZombieClass": "ZombieBasic",
				"Properties": "RTID(MoonRocketIntroAnim@ZombieProperties)",
				"ResourceGroups": [
					"MoonRocketGroup",
					"ZombieDummyGroup"
				],
				"AudioGroups": [
					"PlantCherryBombAudio"
				],
				"AnimRigClass": "ZombieAnimRig_Tutorial",
				"PopAnim": "POPANIM_MOON_ROCKET_INTRO",
				"HomeWorld": "moon",
				"IsBasicZombie": true
			}
		}

## ZombieProperties code
{
			"aliases": [
				"ZombieMoonRocket"
			],
			"objclass": "ZombieGeneralZmechProps",
			"objdata": {
				"Actions": [
					"RTID(ZombieMoonRocketInitialSetup@ZombieActions)"
				],
				"LifetimeSeconds": 99999,
				"GeneralPhase": 0,
				"HypnoshroomEffectOffset": {
					"x": 999999,
					"y": 999999
				},
				"ShadowOffset": {
					"x": 0,
					"y": 0,
					"z": 0
				},
				"AttackRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 999999,
					"mY": 999999
				},
				"HitRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 0,
					"mY": 200
				},
				"CanSurrender": true,
				"ZombieArmorProps": [
					"RTID(AngerManagement@ArmorTypes)"
				],
				"ArtScale": 0,
				"CollideHypnotizedZombies": "ignore",
				"CollidePlants": "ignore",
				"IgnoreWaterLine": true,
				"SkipHeadDropState": true,
				"SpeedVariance": 0,
				"CanTriggerZombieWin": false,
				"CanBePlantTossedStrong": false,
				"CanBePlantTossedWeak": false,
				"CanSpawnPlantFood": false,
				"ChillInsteadOfFreeze": true,
				"ScoreOverride": 1,
				"FireDamageMultiplier": 0,
				"Cost": 150,
				"EatDPS": 0,
				"ConditionImmunities": [
					{
						"Condition": "chill"
					},
					{
						"Condition": "stun"
					},
					{
						"Condition": "invisibleslow"
					},
					{
						"Condition": "stalled"
					},
					{
						"Condition": "sapped"
					},
					{
						"Condition": "poisoned"
					},
					{
						"Condition": "decaypoison"
					},
					{
						"Condition": "shrinking"
					},
					{
						"Condition": "shrunken"
					},
					{
						"Condition": "contagiouspoison"
					},
					{
						"Condition": "dazeystunned"
					},
					{
						"Condition": "buttered"
					},
					{
						"Condition": "gummed"
					},
					{
						"Condition": "stickybombed"
					},
					{
						"Condition": "hasplantfood"
					},
					{
						"Condition": "invincible"
					},
					{
						"Condition": "bleeding"
					},
					{
						"Condition": "suncarrier50"
					},
					{
						"Condition": "suncarrier100"
					},
					{
						"Condition": "suncarrier250"
					},
					{
						"Condition": "warpingIn"
					},
					{
						"Condition": "warpingOut"
					},
					{
						"Condition": "stackableslow"
					},
					{
						"Condition": "terrified"
					},
					{
						"Condition": "suiciding"
					},
					{
						"Condition": "damageflash"
					}
				],
				"GroundTrackName": "none",
				"Hitpoints": 2,
				"Speed": 0.5,
				"WavePointCost": 900,
				"Weight": 0,
				"#comment": "Main-entity props: invisible, flung away and unhittable; only plays its entry segment (which spawns the body)",
			}
		},
		{
			"aliases": [
				"ZombieMoonRocketVisualInitial"
			],
			"objclass": "ZombieGeneralTreadmillProps",
			"objdata": {
				"Actions": [
					"RTID(ZombieMoonRocketVisualNeutralSetup@ZombieActions)",
					"RTID(ZombieMoonRocketVisualNeutralWait@ZombieActions)",
					"RTID(ZombieMoonRocketNeutralDie@ZombieActions)"
				],
				"LifetimeSeconds": 99999,
				"GeneralPhase": 0,
				"ArtScale": 0.8,
				"ArtCenter": {
					"x": 98,
					"y": 127
				},
				"HypnoshroomEffectOffset": {
					"x": 999999,
					"y": 999999
				},
				"ShadowOffset": {
					"x": 0,
					"y": 0,
					"z": 0
				},
				"AttackRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 999999,
					"mY": 999999
				},
				"HitRect": {
					"mHeight": 1,
					"mWidth": 1,
					"mX": 1,
					"mY": 1
				},
				"CanSurrender": true,
				"ZombieArmorProps": [
					"RTID(AngerManagement@ArmorTypes)"
				],
				"CollideHypnotizedZombies": "ignore",
				"CollidePlants": "ignore",
				"IgnoreWaterLine": true,
				"SkipHeadDropState": true,
				"SpeedVariance": 0,
				"CanTriggerZombieWin": false,
				"CanBePlantTossedStrong": false,
				"CanBePlantTossedWeak": false,
				"CanSpawnPlantFood": false,
				"ChillInsteadOfFreeze": true,
				"ScoreOverride": 1,
				"FireDamageMultiplier": 0,
				"Cost": 150,
				"EatDPS": 0,
				"ConditionImmunities": [
					{
						"Condition": "chill"
					},
					{
						"Condition": "freeze"
					},
					{
						"Condition": "sunbeaned"
					},
					{
						"Condition": "solarflared"
					},
					{
						"Condition": "stun"
					},
					{
						"Condition": "invisibleslow"
					},
					{
						"Condition": "stalled"
					},
					{
						"Condition": "sapped"
					},
					{
						"Condition": "poisoned"
					},
					{
						"Condition": "decaypoison"
					},
					{
						"Condition": "shrinking"
					},
					{
						"Condition": "shrunken"
					},
					{
						"Condition": "contagiouspoison"
					},
					{
						"Condition": "dazeystunned"
					},
					{
						"Condition": "buttered"
					},
					{
						"Condition": "gummed"
					},
					{
						"Condition": "stickybombed"
					},
					{
						"Condition": "hasplantfood"
					},
					{
						"Condition": "invincible"
					},
					{
						"Condition": "bleeding"
					},
					{
						"Condition": "suncarrier50"
					},
					{
						"Condition": "suncarrier100"
					},
					{
						"Condition": "suncarrier250"
					},
					{
						"Condition": "warpingIn"
					},
					{
						"Condition": "warpingOut"
					},
					{
						"Condition": "stackableslow"
					},
					{
						"Condition": "terrified"
					},
					{
						"Condition": "suiciding"
					},
					{
						"Condition": "hypnotized"
					},
					{
						"Condition": "damageflash"
					},
					{
						"Condition": "potionspeed1"
					},
					{
						"Condition": "potionspeed2"
					},
					{
						"Condition": "potionspeed3"
					},
					{
						"Condition": "potiontoughness1"
					},
					{
						"Condition": "potiontoughness2"
					},
					{
						"Condition": "potiontoughness3"
					},
					{
						"Condition": "potionsuper1"
					},
					{
						"Condition": "potionsuper2"
					},
					{
						"Condition": "potionsuper3"
					}
				],
				"GroundTrackName": "none",
				"Hitpoints": 2,
				"Speed": 0.5,
				"WavePointCost": 900,
				"Weight": 0,
				"#comment": "Visual-body props",
			}
		},
		{
			"aliases": [
				"ZombieMoonRocketPlantFireInitial"
			],
			"objclass": "ZombieGeneralZmechProps",
			"objdata": {
				"Actions": [
					"RTID(ZombieMoonRocketJudgeIdle@ZombieActions)",
					"RTID(ZombieMoonRocketPlantFireDie@ZombieActions)"
				],
				"LifetimeSeconds": 99999,
				"GeneralPhase": 0,
				"HypnoshroomEffectOffset": {
					"x": 999999,
					"y": 999999
				},
				"AttackRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 999999,
					"mY": 999999
				},
				"HitRect": {
					"mHeight": 65,
					"mWidth": 40,
					"mX": 10,
					"mY": 10
				},
				"CanSurrender": true,
				"ArtScale": 0.0001,
				"CollideHypnotizedZombies": "ignore",
				"CollidePlants": "ignore",
				"IgnoreWaterLine": true,
				"SkipHeadDropState": true,
				"SpeedVariance": 0,
				"CanTriggerZombieWin": false,
				"CanBePlantTossedStrong": false,
				"CanBePlantTossedWeak": false,
				"CanSpawnPlantFood": false,
				"ChillInsteadOfFreeze": true,
				"ScoreOverride": 1,
				"Cost": 150,
				"EatDPS": 0,
				"ConditionImmunities": [
					{
						"Condition": "potionspeed1"
					},
					{
						"Condition": "potionspeed2"
					},
					{
						"Condition": "potionspeed3"
					},
					{
						"Condition": "potiontoughness1"
					},
					{
						"Condition": "potiontoughness2"
					},
					{
						"Condition": "potiontoughness3"
					},
					{
						"Condition": "potionsuper1"
					},
					{
						"Condition": "potionsuper2"
					},
					{
						"Condition": "potionsuper3"
					},
					{
						"Condition": "speedup1"
					},
					{
						"Condition": "speedup2"
					},
					{
						"Condition": "speedup3"
					},
					{
						"Condition": "speedup4"
					},
					{
						"Condition": "speeddown1"
					},
					{
						"Condition": "speeddown2"
					},
					{
						"Condition": "speeddown3"
					},
					{
						"Condition": "speeddown4"
					},
					{
						"Condition": "chill"
					},
					{
						"Condition": "freeze"
					},
					{
						"Condition": "sunbeaned"
					},
					{
						"Condition": "solarflared"
					},
					{
						"Condition": "stun"
					},
					{
						"Condition": "invisibleslow"
					},
					{
						"Condition": "stalled"
					},
					{
						"Condition": "sapped"
					},
					{
						"Condition": "poisoned"
					},
					{
						"Condition": "decaypoison"
					},
					{
						"Condition": "shrinking"
					},
					{
						"Condition": "shrunken"
					},
					{
						"Condition": "contagiouspoison"
					},
					{
						"Condition": "dazeystunned"
					},
					{
						"Condition": "buttered"
					},
					{
						"Condition": "gummed"
					},
					{
						"Condition": "stickybombed"
					},
					{
						"Condition": "hasplantfood"
					},
					{
						"Condition": "invincible"
					},
					{
						"Condition": "bleeding"
					},
					{
						"Condition": "suncarrier50"
					},
					{
						"Condition": "suncarrier100"
					},
					{
						"Condition": "suncarrier250"
					},
					{
						"Condition": "warpingIn"
					},
					{
						"Condition": "warpingOut"
					},
					{
						"Condition": "stackableslow"
					},
					{
						"Condition": "terrified"
					},
					{
						"Condition": "suiciding"
					},
					{
						"Condition": "damageflash"
					},
					{
						"Condition": "weaken1"
					},
					{
						"Condition": "weaken2"
					},
					{
						"Condition": "weaken3"
					},
					{
						"Condition": "weaken4"
					}
				],
				"GroundTrackName": "none",
				"#comment": "Judge half (zombie-side) props: ArtScale 0 invisible + real hittable HitRect; only death actions attached",
				"Hitpoints": 3000,
				"ZombieArmorProps": [],
				"Speed": 0.5,
				"WavePointCost": 900,
				"Weight": 0
			}
		},
		{
			"aliases": [
				"ZombieMoonRocketZombieFireInitial"
			],
			"objclass": "ZombieGeneralZmechProps",
			"objdata": {
				"Actions": [
					"RTID(ZombieMoonRocketJudgeIdle@ZombieActions)",
					"RTID(ZombieMoonRocketZombieFireDie@ZombieActions)"
				],
				"LifetimeSeconds": 99999,
				"GeneralPhase": 0,
				"HypnoshroomEffectOffset": {
					"x": 999999,
					"y": 999999
				},
				"ShadowOffset": {
					"x": 0,
					"y": 0,
					"z": 0
				},
				"AttackRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 999999,
					"mY": 999999
				},
				"HitRect": {
					"mHeight": 65,
					"mWidth": 40,
					"mX": 10,
					"mY": 10
				},
				"ArtScale": 0.0,
				"CollideHypnotizedZombies": "ignore",
				"CollidePlants": "ignore",
				"IgnoreWaterLine": true,
				"SkipHeadDropState": true,
				"SpeedVariance": 0,
				"CanTriggerZombieWin": false,
				"CanBePlantTossedStrong": false,
				"CanBePlantTossedWeak": false,
				"CanSpawnPlantFood": false,
				"ChillInsteadOfFreeze": true,
				"ScoreOverride": 1,
				"Cost": 150,
				"EatDPS": 0,
				"ConditionImmunities": [
					{
						"Condition": "potionspeed1"
					},
					{
						"Condition": "potionspeed2"
					},
					{
						"Condition": "potionspeed3"
					},
					{
						"Condition": "potiontoughness1"
					},
					{
						"Condition": "potiontoughness2"
					},
					{
						"Condition": "potiontoughness3"
					},
					{
						"Condition": "potionsuper1"
					},
					{
						"Condition": "potionsuper2"
					},
					{
						"Condition": "potionsuper3"
					},
					{
						"Condition": "speedup1"
					},
					{
						"Condition": "speedup2"
					},
					{
						"Condition": "speedup3"
					},
					{
						"Condition": "speedup4"
					},
					{
						"Condition": "speeddown1"
					},
					{
						"Condition": "speeddown2"
					},
					{
						"Condition": "speeddown3"
					},
					{
						"Condition": "speeddown4"
					},
					{
						"Condition": "chill"
					},
					{
						"Condition": "freeze"
					},
					{
						"Condition": "sunbeaned"
					},
					{
						"Condition": "solarflared"
					},
					{
						"Condition": "stun"
					},
					{
						"Condition": "invisibleslow"
					},
					{
						"Condition": "stalled"
					},
					{
						"Condition": "sapped"
					},
					{
						"Condition": "poisoned"
					},
					{
						"Condition": "decaypoison"
					},
					{
						"Condition": "shrinking"
					},
					{
						"Condition": "shrunken"
					},
					{
						"Condition": "contagiouspoison"
					},
					{
						"Condition": "dazeystunned"
					},
					{
						"Condition": "buttered"
					},
					{
						"Condition": "gummed"
					},
					{
						"Condition": "stickybombed"
					},
					{
						"Condition": "hasplantfood"
					},
					{
						"Condition": "invincible"
					},
					{
						"Condition": "bleeding"
					},
					{
						"Condition": "suncarrier50"
					},
					{
						"Condition": "suncarrier100"
					},
					{
						"Condition": "suncarrier250"
					},
					{
						"Condition": "warpingIn"
					},
					{
						"Condition": "warpingOut"
					},
					{
						"Condition": "stackableslow"
					},
					{
						"Condition": "terrified"
					},
					{
						"Condition": "suiciding"
					},
					{
						"Condition": "damageflash"
					},
					{
						"Condition": "weaken1"
					},
					{
						"Condition": "weaken2"
					},
					{
						"Condition": "weaken3"
					},
					{
						"Condition": "weaken4"
					}
				],
				"GroundTrackName": "none",
				"#comment": "Judge half (plant-side) props: same as above",
				"Hitpoints": 3000,
				"ZombieArmorProps": [],
				"Speed": 0.5,
				"WavePointCost": 900,
				"Weight": 0
			}
		},
		{
			"aliases": [
				"ZombieMoonRocketVisualFirePlant"
			],
			"objclass": "ZombieGeneralTreadmillProps",
			"objdata": {
				"Actions": [
					"RTID(ZombieMoonRocketVisualFirePlayPlant@ZombieActions)"
				],
				"LifetimeSeconds": 99999,
				"GeneralPhase": 0,
				"ArtScale": 0.8,
				"ArtCenter": {
					"x": 98,
					"y": 127
				},
				"HypnoshroomEffectOffset": {
					"x": 999999,
					"y": 999999
				},
				"ShadowOffset": {
					"x": 0,
					"y": 0,
					"z": 0
				},
				"AttackRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 999999,
					"mY": 999999
				},
				"HitRect": {
					"mHeight": 1,
					"mWidth": 0,
					"mX": 0,
					"mY": 3000
				},
				"CanSurrender": true,
				"ZombieArmorProps": [
					"RTID(AngerManagement@ArmorTypes)"
				],
				"CollideHypnotizedZombies": "ignore",
				"CollidePlants": "ignore",
				"IgnoreWaterLine": true,
				"SkipHeadDropState": true,
				"SpeedVariance": 0,
				"CanTriggerZombieWin": false,
				"CanBePlantTossedStrong": false,
				"CanBePlantTossedWeak": false,
				"CanSpawnPlantFood": false,
				"ChillInsteadOfFreeze": true,
				"ScoreOverride": 1,
				"FireDamageMultiplier": 0,
				"Cost": 150,
				"EatDPS": 0,
				"ConditionImmunities": [
					{
						"Condition": "chill"
					},
					{
						"Condition": "freeze"
					},
					{
						"Condition": "sunbeaned"
					},
					{
						"Condition": "solarflared"
					},
					{
						"Condition": "stun"
					},
					{
						"Condition": "invisibleslow"
					},
					{
						"Condition": "stalled"
					},
					{
						"Condition": "sapped"
					},
					{
						"Condition": "poisoned"
					},
					{
						"Condition": "decaypoison"
					},
					{
						"Condition": "shrinking"
					},
					{
						"Condition": "shrunken"
					},
					{
						"Condition": "contagiouspoison"
					},
					{
						"Condition": "dazeystunned"
					},
					{
						"Condition": "buttered"
					},
					{
						"Condition": "gummed"
					},
					{
						"Condition": "stickybombed"
					},
					{
						"Condition": "hasplantfood"
					},
					{
						"Condition": "invincible"
					},
					{
						"Condition": "bleeding"
					},
					{
						"Condition": "suncarrier50"
					},
					{
						"Condition": "suncarrier100"
					},
					{
						"Condition": "suncarrier250"
					},
					{
						"Condition": "warpingIn"
					},
					{
						"Condition": "warpingOut"
					},
					{
						"Condition": "stackableslow"
					},
					{
						"Condition": "terrified"
					},
					{
						"Condition": "suiciding"
					},
					{
						"Condition": "hypnotized"
					},
					{
						"Condition": "damageflash"
					},
					{
						"Condition": "potionspeed1"
					},
					{
						"Condition": "potionspeed2"
					},
					{
						"Condition": "potionspeed3"
					},
					{
						"Condition": "potiontoughness1"
					},
					{
						"Condition": "potiontoughness2"
					},
					{
						"Condition": "potiontoughness3"
					},
					{
						"Condition": "potionsuper1"
					},
					{
						"Condition": "potionsuper2"
					},
					{
						"Condition": "potionsuper3"
					}
				],
				"GroundTrackName": "none",
				"Hitpoints": 2,
				"Speed": 0.5,
				"WavePointCost": 900,
				"Weight": 0,
				"#comment": "Launch visual props: visible; plays the liftoff segment then destroys itself",
				"TimeToKillInSeconds": 3.0
			}
		},
		{
			"aliases": [
				"ZombieMoonRocketVisualFireZombie"
			],
			"objclass": "ZombieGeneralTreadmillProps",
			"objdata": {
				"Actions": [
					"RTID(ZombieMoonRocketVisualFirePlayZombie@ZombieActions)"
				],
				"LifetimeSeconds": 99999,
				"GeneralPhase": 0,
				"ArtScale": 0.8,
				"ArtCenter": {
					"x": 98,
					"y": 127
				},
				"HypnoshroomEffectOffset": {
					"x": 999999,
					"y": 999999
				},
				"ShadowOffset": {
					"x": 0,
					"y": 0,
					"z": 0
				},
				"AttackRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 999999,
					"mY": 999999
				},
				"HitRect": {
					"mHeight": 1,
					"mWidth": 0,
					"mX": 0,
					"mY": 3000
				},
				"CanSurrender": true,
				"ZombieArmorProps": [
					"RTID(AngerManagement@ArmorTypes)"
				],
				"CollideHypnotizedZombies": "ignore",
				"CollidePlants": "ignore",
				"IgnoreWaterLine": true,
				"SkipHeadDropState": true,
				"SpeedVariance": 0,
				"CanTriggerZombieWin": false,
				"CanBePlantTossedStrong": false,
				"CanBePlantTossedWeak": false,
				"CanSpawnPlantFood": false,
				"ChillInsteadOfFreeze": true,
				"ScoreOverride": 1,
				"FireDamageMultiplier": 0,
				"Cost": 150,
				"EatDPS": 0,
				"ConditionImmunities": [
					{
						"Condition": "chill"
					},
					{
						"Condition": "freeze"
					},
					{
						"Condition": "sunbeaned"
					},
					{
						"Condition": "solarflared"
					},
					{
						"Condition": "stun"
					},
					{
						"Condition": "invisibleslow"
					},
					{
						"Condition": "stalled"
					},
					{
						"Condition": "sapped"
					},
					{
						"Condition": "poisoned"
					},
					{
						"Condition": "decaypoison"
					},
					{
						"Condition": "shrinking"
					},
					{
						"Condition": "shrunken"
					},
					{
						"Condition": "contagiouspoison"
					},
					{
						"Condition": "dazeystunned"
					},
					{
						"Condition": "buttered"
					},
					{
						"Condition": "gummed"
					},
					{
						"Condition": "stickybombed"
					},
					{
						"Condition": "hasplantfood"
					},
					{
						"Condition": "invincible"
					},
					{
						"Condition": "bleeding"
					},
					{
						"Condition": "suncarrier50"
					},
					{
						"Condition": "suncarrier100"
					},
					{
						"Condition": "suncarrier250"
					},
					{
						"Condition": "warpingIn"
					},
					{
						"Condition": "warpingOut"
					},
					{
						"Condition": "stackableslow"
					},
					{
						"Condition": "terrified"
					},
					{
						"Condition": "suiciding"
					},
					{
						"Condition": "hypnotized"
					},
					{
						"Condition": "damageflash"
					},
					{
						"Condition": "potionspeed1"
					},
					{
						"Condition": "potionspeed2"
					},
					{
						"Condition": "potionspeed3"
					},
					{
						"Condition": "potiontoughness1"
					},
					{
						"Condition": "potiontoughness2"
					},
					{
						"Condition": "potiontoughness3"
					},
					{
						"Condition": "potionsuper1"
					},
					{
						"Condition": "potionsuper2"
					},
					{
						"Condition": "potionsuper3"
					}
				],
				"GroundTrackName": "none",
				"Hitpoints": 2,
				"Speed": 0.5,
				"WavePointCost": 900,
				"Weight": 0,
				"#comment": "Same as above (zombie side)",
				"TimeToKillInSeconds": 3.0
			}
		},
		{
			"aliases": [
				"ZombieMoonRocketVisualEndLevelWait"
			],
			"objclass": "ZombieGeneralCaesarProps",
			"objdata": {
				"Actions": [
					"RTID(ZombieMoonRocketEndLevelWait@ZombieActions)",
					"RTID(KelYourselfDying_Enter@ZombieActions)"
				],
				"LifetimeSeconds": 99999999,
				"GeneralPhase": 0,
				"HypnoshroomEffectOffset": {
					"x": 999999,
					"y": 999999
				},
				"ShadowOffset": {
					"x": 0,
					"y": 0,
					"z": 0
				},
				"AttackRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 999999,
					"mY": 999999
				},
				"HitRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 0,
					"mY": 200
				},
				"GridExtents": {
					"mX": 0,
					"mY": 0
				},
				"CanSurrender": true,
				"ZombieArmorProps": [
					"RTID(AngerManagement@ArmorTypes)"
				],
				"ArtScale": 0,
				"CollideHypnotizedZombies": "ignore",
				"CollidePlants": "ignore",
				"IgnoreWaterLine": true,
				"SkipHeadDropState": true,
				"SpeedVariance": 0,
				"CanTriggerZombieWin": false,
				"CanBePlantTossedStrong": false,
				"CanBePlantTossedWeak": false,
				"CanSpawnPlantFood": false,
				"ChillInsteadOfFreeze": true,
				"ScoreOverride": 0.5,
				"FireDamageMultiplier": 0,
				"Cost": 150,
				"EatDPS": 0,
				"ConditionImmunities": [
					{
						"Condition": "chill"
					},
					{
						"Condition": "stun"
					},
					{
						"Condition": "invisibleslow"
					},
					{
						"Condition": "stalled"
					},
					{
						"Condition": "sapped"
					},
					{
						"Condition": "poisoned"
					},
					{
						"Condition": "decaypoison"
					},
					{
						"Condition": "shrinking"
					},
					{
						"Condition": "shrunken"
					},
					{
						"Condition": "contagiouspoison"
					},
					{
						"Condition": "dazeystunned"
					},
					{
						"Condition": "butter"
					},
					{
						"Condition": "gummed"
					},
					{
						"Condition": "stickybombed"
					},
					{
						"Condition": "hasplantfood"
					},
					{
						"Condition": "invincible"
					},
					{
						"Condition": "bleeding"
					},
					{
						"Condition": "suncarrier50"
					},
					{
						"Condition": "suncarrier100"
					},
					{
						"Condition": "suncarrier250"
					},
					{
						"Condition": "warpingIn"
					},
					{
						"Condition": "warpingOut"
					},
					{
						"Condition": "stackableslow"
					},
					{
						"Condition": "terrified"
					},
					{
						"Condition": "suiciding"
					},
					{
						"Condition": "damageflash"
					}
				],
				"GroundTrackName": "none",
				"Hitpoints": 2000000000,
				"Speed": 0.5,
				"WavePointCost": 900,
				"Weight": 0,
				"#comment": "Level-end entity props: invisible + extremely high HP; the engine triggers Retreat to clear it when the level ends",
			}
		},
		{
			"aliases": [
				"ZombieMoonRocketCrosshair"
			],
			"objclass": "ZombieGeneralZmechProps",
			"objdata": {
				"Actions": [
					"RTID(ZombieMoonRocketCrosshairPlay@ZombieActions)"
				],
				"LifetimeSeconds": 99999,
				"GeneralPhase": 0,
				"ArtCenter": {
					"x": 98,
					"y": 140
				},
				"HypnoshroomEffectOffset": {
					"x": 999999,
					"y": 999999
				},
				"ShadowOffset": {
					"x": 0,
					"y": 0,
					"z": 0
				},
				"AttackRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 999999,
					"mY": 999999
				},
				"HitRect": {
					"mHeight": 1,
					"mWidth": 0,
					"mX": 0,
					"mY": 2000
				},
				"GridExtents": {
					"mX": 0,
					"mY": 0
				},
				"CanSurrender": false,
				"ZombieArmorProps": [],
				"ArtScale": 1.1,
				"CollideHypnotizedZombies": "ignore",
				"CollidePlants": "ignore",
				"IgnoreWaterLine": true,
				"SkipHeadDropState": true,
				"SpeedVariance": 0,
				"CanTriggerZombieWin": false,
				"CanBePlantTossedStrong": false,
				"CanBePlantTossedWeak": false,
				"CanSpawnPlantFood": false,
				"ChillInsteadOfFreeze": true,
				"ScoreOverride": 1,
				"FireDamageMultiplier": 0,
				"Cost": 150,
				"EatDPS": 0,
				"ConditionImmunities": [
					{
						"Condition": "chill"
					},
					{
						"Condition": "freeze"
					},
					{
						"Condition": "sunbeaned"
					},
					{
						"Condition": "solarflared"
					},
					{
						"Condition": "stun"
					},
					{
						"Condition": "invisibleslow"
					},
					{
						"Condition": "stalled"
					},
					{
						"Condition": "sapped"
					},
					{
						"Condition": "poisoned"
					},
					{
						"Condition": "decaypoison"
					},
					{
						"Condition": "shrinking"
					},
					{
						"Condition": "shrunken"
					},
					{
						"Condition": "contagiouspoison"
					},
					{
						"Condition": "dazeystunned"
					},
					{
						"Condition": "buttered"
					},
					{
						"Condition": "gummed"
					},
					{
						"Condition": "stickybombed"
					},
					{
						"Condition": "hasplantfood"
					},
					{
						"Condition": "invincible"
					},
					{
						"Condition": "bleeding"
					},
					{
						"Condition": "suncarrier50"
					},
					{
						"Condition": "suncarrier100"
					},
					{
						"Condition": "suncarrier250"
					},
					{
						"Condition": "warpingIn"
					},
					{
						"Condition": "warpingOut"
					},
					{
						"Condition": "stackableslow"
					},
					{
						"Condition": "terrified"
					},
					{
						"Condition": "suiciding"
					},
					{
						"Condition": "damageflash"
					}
				],
				"GroundTrackName": "none",
				"Hitpoints": 1,
				"Speed": 0.5,
				"WavePointCost": 900,
				"Weight": 0,
				"TimeToKillInSeconds": -1,
				"#comment": "crosshair props: unhittable",
			}
		},
		{
			"aliases": [
				"MoonRocketIntroDefault"
			],
			"objclass": "ZombieGeneralTreadmillProps",
			"objdata": {
				"Actions": [
					"RTID(MoonRocketIntroEnter@ZombieActions)",
					"RTID(MoonRocketIntroSpawn@CurrentLevel)",
					"RTID(ZombieEmptyDyingAction@ZombieActions)"
				],
				"LifetimeSeconds": 99999999,
				"CanSurrender": true,
				"GeneralPhase": 0,
				"ArtCenter": {
					"x": 9999,
					"y": 9999
				},
				"ShadowOffset": {
					"x": 9999,
					"y": 9999,
					"z": 1.2
				},
				"ConditionImmunities": [
					{
						"Condition": "chill"
					},
					{
						"Condition": "freeze"
					},
					{
						"Condition": "stalled"
					},
					{
						"Condition": "sapped"
					},
					{
						"Condition": "stun"
					},
					{
						"Condition": "butter"
					},
					{
						"Condition": "speedup1"
					},
					{
						"Condition": "speedup2"
					},
					{
						"Condition": "speedup3"
					},
					{
						"Condition": "speedup4"
					},
					{
						"Condition": "terrified"
					},
					{
						"Condition": "potionspeed1"
					},
					{
						"Condition": "potionspeed2"
					},
					{
						"Condition": "potionspeed3"
					},
					{
						"Condition": "potiontoughness1"
					},
					{
						"Condition": "potiontoughness2"
					},
					{
						"Condition": "potiontoughness3"
					},
					{
						"Condition": "potionsuper1"
					},
					{
						"Condition": "potionsuper2"
					},
					{
						"Condition": "potionsuper3"
					},
					{
						"Condition": "sunbeaned"
					},
					{
						"Condition": "haunted"
					},
					{
						"Condition": "icecubed"
					},
					{
						"Condition": "speeddown1"
					},
					{
						"Condition": "speeddown2"
					},
					{
						"Condition": "speeddown3"
					},
					{
						"Condition": "speeddown4"
					},
					{
						"Condition": "invincible"
					},
					{
						"Condition": "gummed"
					},
					{
						"Condition": "iceblocked"
					},
					{
						"Condition": "blockolistunned"
					},
					{
						"Condition": "bloomingheartdebuff"
					}
				],
				"AttackRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 99999,
					"mY": 99999
				},
				"HitRect": {
					"mHeight": 0,
					"mWidth": 0,
					"mX": 0,
					"mY": 1000
				},
				"GridExtents": {
					"mX": 0,
					"mY": 0
				},
				"StreetOffset": {
					"x": 0,
					"y": 0
				},
				"HypnoshroomEffectOffset": {
					"x": 99999,
					"y": 99999
				},
				"CollideHypnotizedZombies": "ignore",
				"CollidePlants": "ignore",
				"SkipHeadDropState": true,
				"IsSpawnedFlying": true,
				"CanTriggerZombieWin": false,
				"CanBePlantTossedStrong": false,
				"CanBePlantTossedWeak": false,
				"CanSpawnPlantFood": false,
				"ChillInsteadOfFreeze": true,
				"IgnoreWaterLine": true,
				"EatDPS": 0,
				"ZombieArmorProps": [
					"RTID(InvincibleArmor@ArmorTypes)"
				],
				"GroundTrackName": "ground_swatch",
				"Hitpoints": 1,
				"Speed": 4,
				"SpeedVariance": 0,
				"ScoreOverride": 0.5,
				"WavePointCost": 2000,
				"Weight": 4000,
				"ZombieStats": [
					{
						"Type": "toughness",
						"Value": "toughness8"
					},
					{
						"Type": "speed",
						"Value": "5way"
					}
				]
			}
		},
		{
			"aliases": [
				"MoonRocketIntroAnim"
			],
			"objclass": "ZombiePropertySheet",
			"objdata": {
				"ArtCenter": {
					"x": 90,
					"y": 120
				},
				"ArtScale":0.8,
				"AttackRect": {
					"mHeight": 80,
					"mWidth": 20,
					"mX": 99999,
					"mY": 99999
				},
				"CanSpawnPlantFood": false,
				"Cost": 150,
				"EatDPS": 0,
				"GroundTrackName": "none",
				"HitRect": {
					"mHeight": 80,
					"mWidth": 42,
					"mX": 99999,
					"mY": 99999
				},
				"Hitpoints": 3600,
				"HypnoshroomEffectOffset": {
					"x": 99999,
					"y": 99999
				},
				"ScaledProps": [
					{
						"Arg1": 1.3,
						"Arg2": 0.05,
						"Formula": "standard",
						"Key": "Hitpoints"
					},
					{
						"Arg1": 1.3,
						"Arg2": 0.05,
						"Formula": "standard",
						"Key": "EatDPS"
					},
					{
						"Formula": "constant",
						"Key": "Speed"
					},
					{
						"Formula": "constant",
						"Key": "WavePointCost"
					}
				],
				"ShadowOffset": {
					"x": 5,
					"y": 0,
					"z": 1.4
				},
				"SkipHeadDropState": true,
				"Speed": 0.22,
				"WavePointCost": 600,
				"Weight": 1000,
				"ZombieStats": [
					{
						"Type": "toughness",
						"Value": "toughness1"
					},
					{
						"Type": "speed",
						"Value": "speed3"
					}
				]
			}
		}

## ZombieActions code
	{
			"objclass": "ZombieDropActionDefinition",
			"aliases": [
				"ZombieMoonRocketInitialSetup"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Entering",
				"PhaseAfter": "Destroy",
				"Animation": "spawn_body",
				"#comment": "Main entity: on entry plays the empty spawn_body segment (frames inside it spawn the body), then K!I!LL!S! I!TS!EL!F!",
			}
		},
		{
			"objclass": "ZombiePlayAnimationActionDefinition",
			"aliases": [
				"ZombieMoonRocketVisualNeutralSetup"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Entering",
				"PhaseAfter": "Attacking",
				"AnimationToPlay": "visual_setup",
				"CanPickAgain": true,
				"#comment": "The body",
			}
		},
		{
			"objclass": "ZombiePlayAnimationActionDefinition",
			"aliases": [
				"ZombieMoonRocketVisualNeutralWait"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Attacking",
				"PhaseAfter": "Attacking",
				"AnimationToPlay": "idle_plant",
				"CanPickAgain": true
			}
		},
		{
			"objclass": "ZombieDropActionDefinition",
			"aliases": [
				"ZombieMoonRocketNeutralDie"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Dying",
				"PhaseAfter": "Destroy",
				"Animation": "idle_plant",
				"AwardDrop": "RTID(NoDrop@.)"
			}
		},
		{
			"objclass": "ZombieDropActionDefinition",
			"aliases": [
				"ZombieMoonRocketPlantFireDie"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Dying",
				"PhaseAfter": "Destroy",
				"Animation": "die_plant",
				"#comment": "Zombie-side half destroyed: plays the empty die_plant segment (frames inside it spawn the launch visual + clear the body + clear the opposite judge), then K!I!LL!S! I!TS!EL!F!",
				"AwardDrop": "RTID(NoDrop@.)"
			}
		},
		{
			"objclass": "ZombieDropActionDefinition",
			"aliases": [
				"ZombieMoonRocketZombieFireDie"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Dying",
				"PhaseAfter": "Destroy",
				"Animation": "die_zombie",
				"#comment": "Plant-side half eaten: plays die_zombie",
				"AwardDrop": "RTID(NoDrop@.)"
			}
		},
		{
			"objclass": "ZombiePlayAnimationActionDefinition",
			"aliases": [
				"ZombieMoonRocketVisualFirePlayPlant"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Entering",
				"PhaseAfter": "Destroy",
				"AnimationToPlay": "animation_02_plant",
				"CanPickAgain": true
			}
		},
		{
			"objclass": "ZombiePlayAnimationActionDefinition",
			"aliases": [
				"ZombieMoonRocketVisualFirePlayZombie"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Entering",
				"PhaseAfter": "Destroy",
				"AnimationToPlay": "animation_02_zombie",
				"CanPickAgain": true
			}
		},
		{
			"objclass": "ZombiePlayAnimationActionDefinition",
			"aliases": [
				"ZombieMoonRocketCrosshairPlay"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Entering",
				"AnimationToPlay": "in",
				"CanPickAgain": true
			}
		},
		{
			"objclass": "ZombiePlayAnimationActionDefinition",
			"aliases": [
				"ZombieMoonRocketEndLevelWait"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Entering",
				"PhaseAfter": "Entering",
				"AnimationToPlay": "idle",
				"CanPickAgain": true
			}
		},
		{
			"objclass": "ZombieDropActionDefinition",
			"aliases": [
				"KelYourselfDying_Enter"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Entering",
				"PhaseAfter": "Destroy",
				"Animation": "",
				"AwardDrop": "RTID(NoDrops@.)"
			}
		},
		{
			"objclass": "ZombieDropActionDefinition",
			"aliases": [
				"KelYourselfRetreat"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Retreat",
				"PhaseAfter": "Destroy",
				"Animation": "",
				"AwardDrop": "RTID(NoDrops@.)"
			}
		},
		{
			"objclass": "ZombiePlayAnimationActionDefinition",
			"aliases": [
				"ZombieMoonRocketIntroEntering"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 3,
				"RepeatMax": 3,
				"Phase": "Entering",
				"PhaseAfter": "Attacking",
				"AnimationToPlay": "missile_lock_reticle",
				"CanPickAgain": false
			}
		},
		{
			"objclass": "ZombieDropActionDefinition",
			"aliases": [
				"ZombieMoonRocketIntroSpawn"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Attacking",
				"PhaseAfter": "Destroy",
				"Invulnerable": "true",
				"SoundOnStart": "Play_Pilot_AirStrike",
				"Animation": "missile_lock_reticle",
				"AwardDrop": "RTID(ZombieMoonRocketIntroSpawnDrops@.)"
			}
		},
		{
			"objclass": "ZombieDropProps",
			"aliases": [
				"ZombieMoonRocketIntroSpawnDrops"
			],
			"objdata": {
				"Zombies": [
					{
						"Type": "moon_rocket_intro_anim",
						"Hypnotized": false,
						"TossGridXDelta": 0,
						"TossGridYDelta": 0,
						"SpawnGridZDelta": 0,
						"TossDuration": 0,
						"TossApexHeight": 0
					},
					{
						"Type": "moon_rocket_clear_ground",
						"Hypnotized": false,
						"TossGridXDelta": 0,
						"TossGridYDelta": 0,
						"SpawnGridZDelta": 0,
						"TossDuration": 0,
						"TossApexHeight": 0
					}
				]
			}
		},
		{
			"objclass": "ZombieIdleActionDefinition",
			"aliases": [
				"ZombieMoonRocketJudgeIdle"
			],
			"objdata": {
				"#comment": "Judge's Entering empty action (modelled on the official War10LawnOverlayTriggerIdle invisible trigger): plays no animation segment (every dual segment carries spawn side-effects), stays in Entering forever awaiting a hit, and only switches to the Dying action when killed",
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Phase": "Entering",
				"CanPickAgain": true,
				"MinDuration": 999999,
				"MaxDuration": 999999
			}
		},
		{
			"objclass": "ZombiePlayAnimationActionDefinition",
			"aliases": [
				"MoonRocketIntroEnter"
			],
			"objdata": {
				"Weight": 50,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"Invulnerable": true,
				"Phase": "Entering",
				"PhaseAfter": "Attacking",
				"AnimationToPlay": "idle",
				"CanPickAgain": false
			}
		},
		{
			"comment":"This is an example — how many to spawn and where must be customised for this object in the level.",
			"objclass": "ZombieDropZombiesOnBoardActionDefinition",
			"aliases": [
				"MoonRocketIntroSpawn"
			],
			"objdata": {
				"Weight": 1,
				"RepeatMin": 0,
				"RepeatMax": 0,
				"ColumnEnd": 7,
				"ColumnStart": 4,
				"MinSpawn": "0",
				"MaxSpawn": "0",
				"CenterOnInstigator": false,
				"ZombieNames": [
					"moon_rocket_intro_anim"
				],
				"ZombieWeights": [
					100
				],
				"TimeBeforeSpawn": 1.2,
				"ZombieFallTime": 0,
				"Phase": "Attacking",
				"PhaseAfter": "Destroy",
				"RampUpAnimation": "idle",
				"LoopingAnimation": "idle",
				"RampDownAnimation": "idle",
				"EffectTypeToShow": "",
				"DropAudioEvent": ""
			}
		}

## ProjectileTypes code
		{
			"#comment": "Moon Floor — thanks to Teacher Nuclear Beet, love ya mua"
		},
		{
			"#comment": "If the tile is empty, spawn a placeholder crack; if it isn't, spawn a non-placeholder crack",
			"objclass": "SnowieProjectileProps",
			"aliases": [
				"moon_ground_spawn"
			],
			"objdata": {
				"BaseDamage": 0,
				"ClassName": "SnowieProjectile",
				"InitialPierceChance": 2000000000,
				"PierceChanceReductionPerHit": 1,
				"FriendlyFire": false,
				"FriendlyFireCanHitOwner": false,
				"LifeTime": 0.01,
				"Pierces": false,
				"DiesOnImpact": true,
				"HasShadow": false,
				"EntitiesToSpawn": [
					{
						"ActionType": "spawn_grid",
						"ActionArgs": "Type:moon_all_ground, IgnoreGridLayers",
						"ActionOwner": "Projectile",
						"ActivateOn": "Collision"
					},
					{
						"ActionType": "spawn_grid",
						"ActionArgs": "Type:moon_ground, IgnoreGridLayers",
						"ActionOwner": "Projectile",
						"ActivateOn": "LifeTimeEnded"
					}
				],
				"DamageFlags": [
					"no_flash",
					"shooter"
				],
				"CollisionFlags": [
					"plants"
				],
				"InitialVelocity": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					}
				],
				"InitialScale": {
					"Min": 0,
					"Max": 0
				},
				"AttachedPAM": "POPANIM_EFFECTS_SUN",
				"AttachedPAMOffset": {
					"x": 0,
					"y": 0
				},
				"AttachedPAMEffectOffset": {
					"x": 0,
					"y": 0
				},
				"AttachedPAMAnimationToPlay": [
					"animation"
				],
				"CollisionRect": {
					"mX": 0,
					"mY": 0,
					"mWidth": 25,
					"mHeight": 25
				},
				"ImpactSoundEvent": "",
				"ImpactSoundThrottleTimer": 0.075,
				"ImpactPAM": "",
				"ImpactPAMAnimationToPlay": [
					""
				],
				"ImpactOffset": [
					{
						"Min": 9999,
						"Max": 9999
					},
					{
						"Min": 9999,
						"Max": 9999
					}
				]
			}
		},
		{
			"objclass": "ProjectilePropertySheet",
			"aliases": [
				"moon_rocket_impact_plant"
			],
			"objdata": {
				"BaseDamage": 600,
				"SplashDamage": 300,
				"SplashRadius": 2.07,
				"ImpactSoundForce": true,
				"ShakeBoardOnSplash": true,
				"CollisionFlags": [
					"ground"
				],
				"DamageFlags": [
					"lobbed",
					"fire",
					"ash_death",
					"shooter"
				],
				"InitialVelocity": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": -1000,
						"Max": -1000
					}
				],
				"InitialAcceleration": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					}
				],
				"InitialScale": {
					"Min": 1,
					"Max": 1
				},
				"AttachedPAM": "POPANIM_MOON_ROCKET_PROJECTILE_HIT",
				"AttachedPAMAnimationToPlay": [
					"animation"
				],
				"AttachedPAMOffset": {
					"x": -100,
					"y": -97
				},
				"CollisionRect": {
					"mX": -15,
					"mY": -15,
					"mWidth": 30,
					"mHeight": 30
				},
				"ImpactPAM": "POPANIM_MOON_ROCKET_PROJECTILE_HIT",
				"ImpactPAMAnimationToPlay": [
					"animation_02"
				],
				"ImpactOffset": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": -15,
						"Max": -15
					}
				],
				"ImpactSoundEvent": "Play_CherryBomb"
			}
		},
		{
			"objclass": "SnowieProjectileProps",
			"aliases": [
				"moon_rocket_impact_zombie"
			],
			"objdata": {
				"BaseDamage": 12000,
				"ClassName": "SnowieProjectile",
				"FriendlyFire": false,
				"HasShadow": true,
				"FriendlyFireCanHitOwner": false,
				"ShakeBoardOnSplash": true,
				"ImpactSoundForce": true,
				"LifeTime": -1,
				"Pierces": false,
				"DiesOnImpact": true,
				"EntitiesToSpawn": [
					{
						"ActionType": "spawn_projectile",
						"ActionArgs": "Type:MoonRocketDamage,OffsetByGrid,mX:-1,mY:-1,mZ:100",
						"ActionOwner": "Projectile",
						"ActivateOn": "Collision"
					},
					{
						"ActionType": "spawn_projectile",
						"ActionArgs": "Type:MoonRocketDamage,OffsetByGrid,mX:-1,mY:0,mZ:100",
						"ActionOwner": "Projectile",
						"ActivateOn": "Collision"
					},
					{
						"ActionType": "spawn_projectile",
						"ActionArgs": "Type:MoonRocketDamage,OffsetByGrid,mX:-1,mY:1,mZ:100",
						"ActionOwner": "Projectile",
						"ActivateOn": "Collision"
					},
					{
						"ActionType": "spawn_projectile",
						"ActionArgs": "Type:MoonRocketDamage,OffsetByGrid,mX:0,mY:-1,mZ:100",
						"ActionOwner": "Projectile",
						"ActivateOn": "Collision"
					},
					{
						"ActionType": "spawn_projectile",
						"ActionArgs": "Type:MoonRocketDamage,OffsetByGrid,mX:0,mY:1,mZ:100",
						"ActionOwner": "Projectile",
						"ActivateOn": "Collision"
					},
					{
						"ActionType": "spawn_projectile",
						"ActionArgs": "Type:MoonRocketDamage,OffsetByGrid,mX:1,mY:-1,mZ:100",
						"ActionOwner": "Projectile",
						"ActivateOn": "Collision"
					},
					{
						"ActionType": "spawn_projectile",
						"ActionArgs": "Type:MoonRocketDamage,OffsetByGrid,mX:1,mY:0,mZ:100",
						"ActionOwner": "Projectile",
						"ActivateOn": "Collision"
					},
					{
						"ActionType": "spawn_projectile",
						"ActionArgs": "Type:MoonRocketDamage,OffsetByGrid,mX:1,mY:1,mZ:100",
						"ActionOwner": "Projectile",
						"ActivateOn": "Collision"
					}
				],
				"CollisionFlags": [
					"ground",
					"griditems",
					"plants",
					"low_plants",
					"tall_plants",
					"ground_plants",
					"normal_plants"
				],
				"DamageFlags": [
					"lobbed",
					"fire",
					"shooter"
				],
				"InitialVelocity": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": -1000.0,
						"Max": -1000.0
					}
				],
				"InitialAcceleration": [
					{
						"Min": 0.0,
						"Max": 0.0
					},
					{
						"Min": 0.0,
						"Max": 0.0
					},
					{
						"Min": 0,
						"Max": 0
					}
				],
				"InitialScale": {
					"Min": 1.0,
					"Max": 1.0
				},
				"AttachedPAM": "POPANIM_MOON_ROCKET_PROJECTILE_HIT",
				"AttachedPAMOffset": {
					"x": -100,
					"y": -97
				},
				"AttachedPAMEffectOffset": {
					"x": 0.0,
					"y": 0.0
				},
				"AttachedPAMAnimationToPlay": [
					"animation"
				],
				"CollisionRect": {
					"mX": -15.0,
					"mY": -15.0,
					"mWidth": 30.0,
					"mHeight": 30.0
				},
				"ImpactSoundEvent": "Play_CherryBomb",
				"ImpactSoundThrottleTimer": 0.075,
				"ImpactPAM": "POPANIM_MOON_ROCKET_PROJECTILE_HIT",
				"ImpactPAMAnimationToPlay": [
					"animation_02"
				],
				"ImpactOffset": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": -15,
						"Max": -15
					}
				]
			}
		},
		{
			"objclass": "ProjectilePropertySheet",
			"aliases": [
				"MoonRocketDamage"
			],
			"objdata": {
				"BaseDamage": 100,
				"ShakeBoardOnSplash": true,
				"CollisionFlags": [
					"ground",
					"griditems",
					"plants",
					"low_plants",
					"tall_plants",
					"ground_plants",
					"normal_plants"
				],
				"DamageFlags": [
					"lobbed",
					"fire",
					"shooter"
				],
				"InitialVelocity": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": -1000,
						"Max": -1000
					}
				],
				"InitialAcceleration": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					}
				],
				"InitialScale": {
					"Min": 1e-06,
					"Max": 1e-06
				},
				"AttachedPAM": "",
				"AttachedPAMAnimationToPlay": [
					""
				],
				"AttachedPAMOffset": {
					"x": -100,
					"y": -97
				},
				"CollisionRect": {
					"mX": -15,
					"mY": -15,
					"mWidth": 30,
					"mHeight": 30
				},
				"ImpactPAM": "",
				"ImpactPAMAnimationToPlay": [
					""
				],
				"ImpactOffset": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					}
				],
				"ImpactSoundEvent": ""
			}
		},
		{
			"objclass": "SnowieProjectileProps",
			"aliases": [
				"MoonRocketClearGround"
			],
			"objdata": {
				"BaseDamage": 12000,
				"ClassName": "SnowieProjectile",
				"FriendlyFire": false,
				"HasShadow": false,
				"InitialPierceChance": 2000000000,
				"PierceChanceReductionPerHit": 1,
				"FriendlyFireCanHitOwner": false,
				"ShakeBoardOnSplash": false,
				"ImpactSoundForce": false,
				"LifeTime": 1,
				"Pierces": true,
				"DiesOnImpact": false,
				"EntitiesToSpawn": [
				],
				"CollisionFlags": [
					"ground",
					"plants",
					"low_plants",
					"tall_plants",
					"ground_plants",
					"normal_plants"
				],
				"DamageFlags": [
					"lobbed",
					"shooter"
				],
				"InitialVelocity": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": -1000.0,
						"Max": -1000.0
					}
				],
				"InitialAcceleration": [
					{
						"Min": 0.0,
						"Max": 0.0
					},
					{
						"Min": 0.0,
						"Max": 0.0
					},
					{
						"Min": 0,
						"Max": 0
					}
				],
				"InitialScale": {
					"Min": 0.001,
					"Max": 0.001
				},
				"AttachedPAM": "",
				"AttachedPAMOffset": {
					"x": -100,
					"y": -97
				},
				"AttachedPAMEffectOffset": {
					"x": 0.0,
					"y": 0.0
				},
				"AttachedPAMAnimationToPlay": [
					""
				],
				"CollisionRect": {
					"mX": -15.0,
					"mY": -15.0,
					"mWidth": 30.0,
					"mHeight": 30.0
				},
				"ImpactSoundEvent": "",
				"ImpactSoundThrottleTimer": 0.075,
				"ImpactPAM": "",
				"ImpactPAMAnimationToPlay": [
					""
				],
				"ImpactOffset": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					}
				]
			}
		},
		{
			"objclass": "SnowieProjectileProps",
			"aliases": [
				"moon_cleaner_test"
			],
			"objdata": {
				"BaseDamage": 1e-05,
				"ClassName": "SnowieProjectile",
				"InitialPierceChance": 2000000000,
				"PierceChanceReductionPerHit": 1,
				"FriendlyFire": true,
				"FriendlyFireCanHitOwner": true,
				"LifeTime": 2,
				"Pierces": true,
				"DiesOnImpact": false,
				"HasShadow": false,
				"EntitiesToSpawn": [
					{
						"ActionType": "transform",
						"ActionArgs": "TransformArgs[Zombie, dummy2], Include[moon_rocket,moon_rocket_visual_initial, moon_rocket_plantfire_initial,moon_rocket_zombiefire_initial,moon_rocket_endlevel_wait]",
						"ActionOwner": "Target",
						"ActivateOn": "Collision"
					}
				],
				"DamageFlags": [
					"shooter",
					"no_flash"
				],
				"CollisionFlags": [
					"all_zombies"
				],
				"InitialVelocity": [
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": 0,
						"Max": 0
					},
					{
						"Min": -1000,
						"Max": -1000
					}
				],
				"InitialScale": {
					"Min": 1,
					"Max": 1
				},
				"AttachedPAM": "POPANIM_EFFECTS_SUN",
				"AttachedPAMOffset": {
					"x": -9999,
					"y": -9999
				},
				"AttachedPAMEffectOffset": {
					"x": 0,
					"y": 0
				},
				"AttachedPAMAnimationToPlay": [
					"animation"
				],
				"CollisionRect": {
					"mX": -15,
					"mY": -15,
					"mWidth": 45,
					"mHeight": 45
				},
				"ImpactSoundEvent": "",
				"ImpactSoundThrottleTimer": 0.075,
				"ImpactPAM": "",
				"ImpactPAMAnimationToPlay": [
					""
				],
				"ImpactOffset": [
					{
						"Min": 9999,
						"Max": 9999
					},
					{
						"Min": 9999,
						"Max": 9999
					}
				]
			}
		}

## PropertySheet code (the plant/zombie ash & shock declarations live here too, so I don't have to scatter them around)
### Plant section
                    {
						"Type": "pineclone_intro",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": true,
						"IsVisible": false,
						"CanPlantfood": false,
						"HasShadow": true
					},
					{
						"Type": "pineclone_clone_intro",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": true,
						"IsVisible": false,
						"CanPlantfood": false,
						"HasShadow": false
					},
					{
						"Type": "pineclone_clone",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": true,
						"IsVisible": false,
						"CanPlantfood": true,
						"HasShadow": false
					},
					{
						"Type": "cosmicnut_transform",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": true,
						"IsVisible": false,
						"CanPlantfood": false,
						"HasShadow": true
					},
					{
						"Type": "cosmictallnut_transform",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": true,
						"IsVisible": false,
						"CanPlantfood": false,
						"HasShadow": true
					},
                    {
						"Type": "cosmos",
						"CanSink": false,
						"CanPlantfood": false,
						"CanShovel": false,
						"CountsToPlantLoss": true,
						"HasShadow": true,
						"IsVisible": true
					},
					{
						"Type": "cosmos_ground",
						"CanSink": false,
						"CanPlantfood": false,
						"CanShovel": true,
						"CountsToPlantLoss": true,
						"HasShadow": false,
						"IsVisible": true
					},
					{
						"Type": "sweetpotato_tool",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": false,
						"IsVisible": false,
						"CanPlantfood": false,
						"HasShadow": false
					},
					{
						"Type": "cosmicpea_intro",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": true,
						"IsVisible": true,
						"CanPlantfood": false,
						"HasShadow": true
					},
					{
						"Type": "cosmicrepeater_intro",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": true,
						"IsVisible": true,
						"CanPlantfood": false,
						"HasShadow": true
					},
					{
						"Type": "cosmicgatling_intro",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": true,
						"IsVisible": true,
						"CanPlantfood": false,
						"HasShadow": true
					},
					{
						"Type": "darkmatter_dragon",
						"CanSink": false,
						"CountsToPlantLoss": false,
						"CanShovel": false,
						"IsVisible": false,
						"CanPlantfood": false,
						"HasShadow": false
					}
### Zombie section

					{
						"Type": "YanMie",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
                    {
						"Type": "moon",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_armor1",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_armor2",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_armor4",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_flag",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_walker",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_walker_mid",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_walker_nojump",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_walker_teleport",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_walker_mid_teleport",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_walker_nojump_teleport",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "cosmic_imp",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_IMP_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "cosmic_imp_transform",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "cosmic_imp_gargantuar_intro",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "cosmic_imp_gargantuar",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_BIGHEAD_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_GARGANTUAR_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "cosmic_imp_toycar_intro",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "cosmic_imp_bubblegun_Intro",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "cosmic_imp_toycar",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "cosmic_imp_bubblegun",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_IMP_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_ship5000",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_SHIP5000_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_SHIP5000_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "ship5000_caketank",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_SHIP5000_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_SHIP5000_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_imp",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_IMP_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "teleport_moon_walker",
						"AshAnim": "",
						"ShockAnim": "",
						"CountsToZombiesKilled": true,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "teleport_supernova_gargantuar",
						"AshAnim": "",
						"ShockAnim": "",
						"CountsToZombiesKilled": true,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "teleport_moon_teleporter_purple",
						"AshAnim": "",
						"ShockAnim": "",
						"CountsToZombiesKilled": true,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "teleport_moon_teleporter_green",
						"AshAnim": "",
						"ShockAnim": "",
						"CountsToZombiesKilled": true,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_teleporter_purple",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_teleporter_green",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_teleporter_purple_teleport",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_teleporter_green_teleport",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_SHOCK",
						"CountsToZombiesKilled": true,
						"CanBeAshed": true,
						"CanBeShocked": true
					},
					{
						"Type": "moon_rocket",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_rocket_visual_initial",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_rocket_plantfire_initial",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_rocket_zombiefire_initial",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_rocket_visual_fire_plant",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_rocket_visual_fire_zombie",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_rocket_endlevel_wait",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_rocket_crosshair",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_rocket_intro",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					},
					{
						"Type": "moon_rocket_intro_anim",
						"AshAnim": "POPANIM_EFFECTS_ZOMBIE_MOON_ASH",
						"ShockAnim": "POPANIM_EFFECTS_ZOMBIE_IMP_SHOCK",
						"CountsToZombiesKilled": false,
						"CanBeAshed": false,
						"CanBeShocked": false
					}

(Didn't do the costumes, by the way.)
