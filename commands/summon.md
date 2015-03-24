#summon fun stuff

Commands:

```powershell
 /summon Zombie ~ ~1 ~ {IsBaby:1,Riding:{id:Chicken}}
```

```powershell
/summon Zombie ~ ~1 ~ {Equipment:[{Count:1,id:279,tag:{ench:[{id:16,lvl:3}]}},{Count:1,id:301,tag:{ench:[{id:2,lvl:4}]}},{Count:1,id:300,tag:{ench:[{id:4,lvl:3}]}},{Count:1,id:307,tag:{ench:[{id:4,lvl:1}]}},{Count:1,id:310,tag:{ench:[{id:5,lvl:1}]}}],CustomName:Chicken Jockey,CustomNameVisible:1,Attributes:[{Name:generic.maxHealth,Base:100},{Name:generic.movementSpeed,Base:0.5},{Name:generic.attackDamage,Base:10},{Name:generic.followRange,Base:10},{Name:generic.knockbackResistance,Base:10}],IsBaby:1,DropChances:[1.0F,1.0F,1.0F,1.0F,1.0F],Riding:{id:Chicken}}
```

**Slime Block Tornado**
```powershell
summon Slime ~ ~1 ~ {Size:7,Riding:{id:"Slime",Size:6,Riding:{id:"Slime",Size:5,Riding:{id:"Slime",Size:4,Riding:{id:"Slime",Size:3,Riding:{id:"Slime",Size:2,Riding:{id:"Slime",Size:1}}}}}}} 
```

**Rideable EnderDragon and Wither**
```powershell
/summon Minecart ~ ~1 ~ {Riding:{id:"EnderDragon"}}
```
```powershell
/summon Minecart ~ ~1 ~ {Riding:{id:"WitherBoss"}} 
```
(careful with the wither one sometimes he can break minecraft blocks) 

**flying pig**
```powershell
summon Pig ~0 ~0 ~0 {Riding: {id: "Bat"}} 
```

**Mob tower**
(put this in command block) 
```powershell
summon Zombie ~ ~1 ~ {Riding:{id:Slime, Riding:{id:MushroomCow, Riding:{id:Creeper, Riding:{id:Villager, Riding:{id:Skeleton, Riding:{id:Spider, Riding:{id:Chicken, Riding:{id:Pig, Riding:{id:Cow, Riding:{id:Sheep, Riding:{id:PigZombie, Riding:{id:Enderman,Riding:{id:CaveSpider, Riding:{id:SnowMan, Riding:{id:Witch}}}}}}}}}}}}}}}} 
```
And if you want it to fly!
```powershell
summon Zombie ~ ~1 ~ {Riding:{id:Slime, Riding:{id:MushroomCow, Riding:{id:Creeper, Riding:{id:Villager, Riding:{id:Skeleton, Riding:{id:Spider, Riding:{id:Chicken, Riding:{id:Pig, Riding:{id:Cow, Riding:{id:Sheep, Riding:{id:PigZombie, Riding:{id:Enderman,Riding:{id:CaveSpider, Riding:{id:SnowMan, Riding:{id:Witch, Riding:{id:Bat}}}}}}}}}}}}}}}}
