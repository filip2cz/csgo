# How to enable bunnyhoping on custom game
If you are server host, just paste this into console:
command:
```
sv_cheats 1; sv_enablebunnyhopping 1; sv_autobunnyhopping 1; sv_enablebunnyhopping 1; sv_staminamax 0; sv_staminajumpcost 0; sv_staminalandcost 0; sv_staminarecoveryrate 0; sv_airaccelerate 2000; sv_accelerate_use_weapon_speed 0; sv_maxvelocity 3500
```

after this, you can disable cheats with
```
sv_cheats 0
```

## Bunnyhop with scrollup

If you use previous command, you can bunnyhop with just holding spacebar. But on some servers, or if you want to "bunnyhop" in official matches, you cannot do that. You need good timming, or just jump with scrollup on your mouse.

```
bind mwheelup +jump
```

default bind for scrollup is:

```
bind mwheelup invprev
```

source: https://steamcommunity.com/sharedfiles/filedetails/?id=1177879522