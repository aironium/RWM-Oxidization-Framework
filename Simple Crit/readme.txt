[SimpleCrit v0.2 by SioxerNikita]

1) in [core] add `copyFrom: ROOT:Oxidization Framework\Simple Crit\SimpleCrit.copyFrom`

2) In [core] add `@global: SiCrit_CritMultiplier: 2`. You can change the number to any multiplier. 2 is 200% of normal damage, so twice the normal damage.

3) in [core] add `@global: SiCrit_CritChance: 25`. The 25 is the percentage chance of getting a crit, so 25 is 25%.

4) in [core] add `@global: SiCrit_DirectDamage: 10`. The 10 is the direct damage your projectile will do. No need to add directDamage to your normal hit and crit projectiles. Set to 0 if you don't want directDamage.

5) in [core] add `@global: SiCrit_DirectDamage: 15`. The 15 is the area damage your projectile will do. No need to add areaDamage to your normal hit and crit projectiles. Set to 0 if you don't want areaDamage.

6) Add your [turret] and add `@copyFromSection: template_SiCrit_Turret` to it.

7) Add to your [turret] `@define SiCrit_projectile: YourProjectileName` Where YourProjectileName is the name of your normal projectile.

8) Add [projectile_YourProjectileName] and add `@copyFromSection: template_SiCrit_NormalProjectile` to it. Replace YourProjectileName to the name you want for your projectile. Now do what ever you want with your projectile. Remember, don't add directDamage and areaDamage

9) Add [projectile_YourProjectileName_Crit] and add `@copyFromSection: template_SiCrit_CritProjectile` to it. Replace YourProjectileName (keep the _Crit at the end) to the same name as in step 7). Now do what ever you want with your crit projectile.

10) Profit
