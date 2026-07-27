Command 7: Initialize_Datalogs
# [11] Hunter Reference Data
## HunterReferenceData
HunterRankDist=E:80|D:16|C:3.2|B:0.675|A:0.1|S:0.025.
SRankPop≈1:4000000.
SRankVariation=Regional.
NewSRank→MajorNationalEvent.
InterestedParties=Govts|Guilds|Media|ForeignPowers.
## DungeonReferenceData
HDRarity=E:Impossible|D:Impossible|C:ExRare|B:ExRare|A:VeryRare|S:Rare.
SARRarity=E:Impossible|D:Impossible|C:Impossible|B:ExRare|A:VeryRare|S:Rare.
GateRankDist=E:80|D:16|C:3.2|B:0.675|A:0.1|S:0.025.
GateSignificance=E:Routine|D:Professional|C:RaidReq|B:GuildInterest|A:MajorPublicEvent|S:NationalCatastrophe.
## PowerScalingReferenceData
StageThreatMap=S2:T2|S3:T3|S4:T4|S5:T4-5|S6:T6|S7:T6-7.
STRScale=10-20:PeakHuman|21-40:Superhuman|41-60:MonsterClass|61-80:Catastrophic|81-100:NLH|101-200:DisasterClass|201-300:CataclysmClass|301-500:MythicClass|500+:EndgameClass.
STRExamples=10-20:BreakDoors+LiftFurniture|21-40:BreakConcrete+BendMetal+LiftVehicles|41-60:PunchWalls+DestroyStoneStructures|61-80:Shockwaves+TearArmoredMonsters|81-100:ArtilleryLevel+DominateOrdinarySRank.
VITScale=10-20:PeakHumanDurability|21-40:SuperhumanResilience|41-60:HeavyArmorDurability|61-80:ExceptionalDurability|81-100:DisasterResistant|101-200:FortressClass|201-300:CataclysmClass|301-500:MythicClass|500+:EndgameClass.
VITExamples=10-20:WeaponVulnerable|21-40:SurviveFatalImpacts|41-60:ResistConventionalWeapons|61-80:EndureDevastatingAttacks|81-100:SurviveStructureDestruction.
AGIScale=10-20:ExceptionalReflexes|21-40:SuperhumanSpeed|41-60:FasterThanSight|61-80:ExtremeMobility|81-100:NLH|101-200:DisasterClass|201-300:CataclysmClass|301-500:MythicClass|500+:EndgameClass.
AGIExamples=10-20:ExceptionalReflexes|21-40:ClearlySuperhuman|41-60:BeyondVisualTracking|61-80:EvadeMostRangedAttacks|81-100:MostHuntersCannotReact.
INTScale=10-20:SmallManaPool|21-40:StableCombatReserves|41-60:CapableSpellcaster|61-80:HighTierSpellcaster|81-100:NLHReserves|101-200:DisasterClass|201-300:CataclysmClass|301-500:MythicClass|500+:EndgameClass.
INTExamples=10-20:LimitedSupernaturalUse|21-40:ReliableCombatUse|41-60:SustainedSpellcasting|61-80:SupportAdvancedAbilities|81-100:TopTierHunterManaReserves.
SENScale=10-20:ExceptionalAwareness|21-40:ReliableManaPerception|41-60:AdvancedAwareness|61-80:BattlefieldDominance|81-100:NLHPerception|101-200:DisasterClass|201-300:CataclysmClass|301-500:MythicClass|500+:EndgameClass.
SENExamples=10-20:ExceptionalAwareness|21-40:ReliableManaDetection|41-60:DetectAmbushes|61-80:ManaMapping|81-100:BeyondOrdinaryHunterPerception.
## SystemRewardReferenceData
DailyLootBox=1-50:Trash|51-69:BasicCons|70-93:SystemGold|94-100:PSIKey.
TrashExamples=Pens|Paper|CheapFlashlights.
BasicConsExamples=HPPotion|MPPotion|Antivenom|Bandages.
## CharacterProgressionReferenceData
LvlUp=+1STR|+1AGI|+1VIT|+1INT|+1SEN|+5FreeAttrs.
LvlGrowth=10AttrPts.
## LootAndRewardsReferenceData
OrdinaryLoot=1-55:None|56-80:SystemGold|81-93:SourceMat|94-97:SourceCons|98-99:SourceEq|100:SourceWpn.
EliteLoot=1-25:GoldOnly|26-50:DoubleGold|51-70:Mat+Gold|71-80:Cons+Gold|81-90:Eq+Gold|91-97:Wpn+Gold|98-100:RS+Gold.
BossLoot=1-15:Mats|16-30:Cons|31-50:RareEq|51-70:RareWpn|71-85:SignatureItem|86-95:UniqueItem|96-100:MultiDrop.
BossRSChance=B:5|A:15|S:40|Unique:60.
DungeonBossRSChance=B:5|A:10|S:20.
ProfStages=Prof:BasicMastery|AdvProf:SignificantExpertise|MasterProf:ExceptionalMastery.
ChestLoot=1-30:SystemGold|31-50:Cons|51-65:Mats|66-80:EqArmor|81-90:Wpn|91-100:MultiCompatibleDrops.
## TimeManagement
- Cycle: 00:00 Reset.
- Warning: Issue [SYSTEM ALERT: 120min Remaining] at 22:00 if DailyQuest=Incomplete.
- Narrative: Reflect time passage via environmental cues (Sun/Traffic/Quiet).
