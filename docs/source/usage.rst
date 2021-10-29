Hardcore
=====

hcmc.nerdyjohnny.com

.. _rules:

Rules
------------

As much we want this to be a lawless land like in DayZ, there is still some ground rules that are required.

1. No using mods/hacks/glitches/modified clients/unfair advantages.
2. Combat logging via mobs or players is not allowed. Combat logging will result in a tempban and a lost of that current life with items.
3. Raiding is allowed
4. Griefing is only allowed in the sense of raiding. You are allowed to break doors or windows to gain entry into a base. If the base is concealed and windows/doors are not easily accessible, raiders may break up to two blocks on a wall, or freely break blocks until it allows them access to the windows/doors.
5. Spawn camping is not allowed.
6. Building/Basing is not allowed near spawn areas or against WorldGuard boundries.
7. No using teleports/warps/`/home` in combat.
8. No using `/ci` or `/clearinventory` in combat or raids.
9. Use common sense.

Tempbans issues due to a death is non-appealable unless you are killed due to someone breaking rules. Please included this in the ban request and how many lives you had before encountering the rule breaker.

Ban appeals can be submitted at [http://discord.gg/Erg3fCV7zh](http://discord.gg/Erg3fCV7zh) in the #support  channel.

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

