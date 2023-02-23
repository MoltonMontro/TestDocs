Animals
=======

**GUID** *32-digit hexadecimal*: Refer to `GUID </GUID.md>`__
documentation.

**Type** *enum* (``Animal``)

**ID** *uint16*: Must be a unique identifier.

Animal Properties
-----------------

**Health** *uint16*: Total health value.

**Regen** *float*: How often health should be regenerated, in seconds.
After the specified amount of time passes, the animal regains 1 health.
Defaults to 10 seconds.

**Damage** *byte*: Damage dealt to the player per attack.

**Behaviour** *enum* (``Defense``, ``Offense``, ``Ignore``): AI behavior
type. Defense AI will run away when alerted, Offense AI will attack when
alerted, and Ignore AI will run away when attacked.

**Speed_Run** *float*: Running speed in m/s.

**Speed_Walk** *float*: Walking speed in m/s.

**Horizontal_Attack_Range** *float*: Maximum attack range on the
horizontal plane. Defaults to 2.25 meters.

**Horizontal_Vehicle_Attack_Range** *float*: Maximum attack range on the
horizontal plane, when the target is inside a vehicle. Defaults to 4.4
meters squared.

**Vertical_Attack_Range** *float*: Maximum vertical attack range.
Defaults to 2 meters.

**Attack_Interval** *float*: Minimum seconds between attacks. Defaults
to one second. If the attack duration is longer than the attack interval
then the attack duration is used instead.

**Roars** *int*: Total number of roar sounds in Unity. A roar sound is
played when the animal attacks.

**Panics** *int*: Total number of panic sounds in Unity. A panic sound
is played when the animal is startled.

**Attack_Anim_Variants** *int*: Total number of attack animations in
Unity. Defaults to 1.

**Eat_Anim_Variants** *int*: Total number of eat animations in Unity.
Defaults to 1.

**Glance_Anim_Variants** *int*: Total number of glance animations in
Unity. Defaults to 2.

**Startle_Anim_Variants** *int*: Total number of startle animations in
Unity. Defaults to 1.

**Should_Play_Anims_On_Dedicated_Server** *bool*: If animations are
needed on the server, such as due to having complicated triggers tied to
the attack animations. Defaults to false.

Drops
-----

**Reward_ID** *uint16*: ID of the item spawn table to use.

**Reward_XP** *uint*: Amount of experience to reward.

**Reward_Min** *byte*: Minimum amount of item drops to reward. Defaults
to 3.

**Reward_Max** *byte*: Maximum amount of item drops to reward. Defaults
to 4.

**Meat** *uint16*: ID of item to spawn when animal is killed. Deprecated
in favor of Reward_ID.

**Pelt** *uint16*: ID of item to spawn when animal is killed. Deprecated
in favor of Reward_ID.

Localization
------------

**Name** *string*: Animal name in user interfaces.
