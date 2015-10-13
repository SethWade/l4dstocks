#  #

| [L4D1\_GetPlayerZombieClass](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#149) | Returns zombie player L4D1 zombie class |
|:---------------------------------------------------------------------------------------------------|:----------------------------------------|
| [L4D1\_SetPlayerZombieClass](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#161) | Set zombie player L4D1 zombie class     |
| [L4D2\_GetPlayerZombieClass](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#174) | Returns zombie player L4D2 zombie class |
| [L4D2\_SetPlayerZombieClass](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#186) | Set zombie player L4D2 zombie class     |
| [L4D\_IsPlayerGhost](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#199)         | Returns ghost state of zombie player    |
| [L4D\_SetPlayerGhostState](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#211)   | Sets ghost state of zombie player       |
| [L4D\_GetPlayerGhostSpawnState](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#224) | Returns ghost spawn state of zombie player |
| [L4D\_SetPlayerGhostSpawnState](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#236) | Set zombie player's ghost spawn state bits |
| [L4D\_IsPlayerCulling](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#251)       | Returns whether zombie player is culling |
| [L4D\_SetPlayerCullingState](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#262) | Set culling state of zombie player      |
| [L4D\_IsPlayerIncapacitated](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#275) | Returns whether player is incapacitated |
| [L4D\_SetPlayerIncapacitatedState](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#289) | Set player's incapacitated state        |
| [L4D\_GetPlayerShovePenalty](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#302) | Returns survivor player shove penalty   |
| [L4D\_SetPlayerShovePenalty](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#313) | Set survivor player shove penalty       |
| [L4D\_GetTankFrustration](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#326)    | Returns tank player's frustration       |
| [L4D\_SetTankFrustration](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#338)    | Set tank player's frustration           |
| [L4D\_IsPlayerIdle](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#351)          | Returns whether survivor player is idle |
| [L4D\_GetBotOfIdlePlayer](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#362)    | Returns survivor bot of idle survivor player |
| [L4D\_GetIdlePlayerOfBot](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#397)    | Returns idle survivor player of survivor bot |
| [L4D\_GetResourceEntity](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#409)     | Returns resource entity                 |
| [L4D\_GetPlayerResourceData](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#419) | Retrieves client data from the resource entity |
| [L4D\_SetPlayerResourceData](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#451) | Sets client data in the resource entity |
| [L4D\_RemoveWeaponSlot](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#488)      | Removes the weapon from a client's weapon slot |
| [L4D\_RemoveAllWeapons](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#506)      | Removes all weapons from a client       |
| [L4D\_IsFinaleActive](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#521)        | Returns whether the finale is active    |
| [L4D\_HasAnySurvivorLeftSafeArea](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#538) | Returns whether any survivor have left the safe area |
| [L4D\_GetPendingTankPlayer](https://code.google.com/p/l4dstocks/source/browse/l4d_stocks.inc#556)  | Returns pending tank player             |
| L4D2\_SetEntGlow                                                                                   | Set entity glow. This is consider safer and more robust over setting each glow property on their own because glow offset will be check first |
| L4D2\_SetEntGlow\_Type                                                                             | Set entity glow type                    |
| L4D2\_SetEntGlow\_Range                                                                            | Set entity glow range                   |
| L4D2\_SetEntGlow\_MinRange                                                                         | Set entity glow min range               |
| L4D2\_SetEntGlow\_ColorOverride                                                                    | Set entity glow color                   |
| L4D2\_SetEntGlow\_Flashing                                                                         | Set entity glow flashing state          |
| L4D2\_GetPlayerSurvivorGlow                                                                        | Return player survivor glow state       |
| L4D2\_SetPlayerSurvivorGlow                                                                        | Set player's survivor glow active state |
| L4D\_GetPlayerReviveCount                                                                          | Return player current revive count      |
| L4D\_SetPlayerReviveCount                                                                          | Set player revive count                 |
| L4D\_GetPlayerIntensity                                                                            | Return player intensity                 |
| L4D\_GetAvgSurvivorIntensity                                                                       | Returns average survivor intensity      |
| L4D\_SetPlayerIntensity                                                                            | Set player intensity                    |
| L4D\_IsPlayerCalm                                                                                  | Returns whether player is calm          |
| L4D\_SetPlayerCalmState                                                                            | Set player is calm state                |
| L4D\_IsPlayerOnThirdStrike                                                                         | Returns whether player is on third strike |
| L4D\_SetPlayerThirdStrikeState                                                                     | Set player third strike state           |
| L4D\_IsPlayerGoingToDie                                                                            | Returns whether player is going to die  |
| L4D\_SetPlayerIsGoingToDie                                                                         | Set player is going to die state        |
| L4D2\_GetWeaponUpgradeAmmoCount                                                                    | Returns upgraded ammo count for weapon  |
| L4D2\_SetWeaponUpgradeAmmoCount                                                                    | Set upgraded ammo count in weapon       |
| L4D2\_GetWeaponUpgrades                                                                            | Returns weapon upgrades of weapon       |
| L4D2\_SetWeaponUpgrades                                                                            | Set weapon upgrades for weapon          |
| L4D2\_GetInfectedAttacker                                                                          | Returns infected attacker of survivor victim |
| L4D2\_GetSurvivorVictim                                                                            | Returns survivor victim of infected attacker |
| L4D2\_WasPresentAtSurvivalStart                                                                    | Returns whether survivor client was present at survival start |
| L4D2\_SetPresentAtSurvivalStart                                                                    | Sets whether player was present at survival start |
| L4D\_IsPlayerUsingMountedWeapon                                                                    | Returns whether player is using a mounted weapon |
| L4D\_GetPlayerTempHealth                                                                           | Returns player temporarily health       |
| L4D\_SetPlayerTempHealth                                                                           | Set players temporarily health          |
| L4D2\_GetPlayerUseAction                                                                           | Returns player use action               |
| L4D2\_GetPlayerUseActionTarget                                                                     | Returns player use action target        |
| L4D2\_GetPlayerUseActionOwner                                                                      | Returns player use action owner         |
| L4D2\_CreateInstructorHint                                                                         | Creates an instructor hint              |
| L4D2\_StopInstructorHint                                                                           | Stops all instructor hints with name    |