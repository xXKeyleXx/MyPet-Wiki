# Hunger-System

With the Hunger-System is based on saturation. The saturation is a value between **1** and **100**, where **100** is the best and **1** is the worst. After a period of time \(can be set with the `MyPet.HungerSystem.Time` setting\) the saturation decreases and affects other stats of your pet.

## Hitpoints on respawn

When a pet respawns it won't have full hitpoints when the _Saturation_ is below **90**. This table shows how much the saturation affects the hitpoints on respawn:

| Hunger-Points | Hitpoints on respawn |
| :--- | :--- |
| 100-91 | **full** Hitpoints |
| 90-81 | **90%** of max. Hitpoints |
| 80-71 | **80%** of max. Hitpoints |
| 70-61 | **70%** of max. Hitpoints |
| 60-51 | **60%** of max. Hitpoints |
| 50-41 | **50%** of max. Hitpoints |
| 40-31 | **40%** of max. Hitpoints |
| 30-21 | **30%** of max. Hitpoints |
| 20-11 | **20%** of max. Hitpoints |
| 10-2 | **10%** of max. Hitpoints |
| 1 | **1** Hitpoint |

## Skills Affected By Hunger

### Beacon

The lower the saturation the less is the range of the beacon effect.

### Ride

The lower the saturation the slower your pet will run when you ride it.

