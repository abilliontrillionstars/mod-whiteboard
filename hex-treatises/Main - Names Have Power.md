hexcasting addon that allows bypassing the usual truename mechanics for your trusted friends. or naive enemies.

## mechanics
- adds configs to base hex truename behaviors
    - chronicler's-ing yourself
    - change how truename *foci* work
    - patch being *inside* fletcher impeti
- DECIDE: for treatise items, 
    - are they used up, and tracked in playerdata?
    - or do you need to keep them on your person?
        - Patron's Scroll Holder
            - curio item, bundle for treatises

- make a Truename Treatise
    - like Witchery's Taglock Kit, or MnA Player Charm
        - activated with a staff-only pattern, like soulprints
    - bypass Transgress Other mishaps involving that player
        - could have a slew of mixins, 
        - or invade the VM ((not advised))
- Lodequartz Compass
    - provides constant coords of a player, but not reference
- add back in some gloop features?
    - truename coins
    - truename write warning (& Acknowledge Truename)
    - (maybe) renew truename
        - would need more balancing
- contracts? maybe unoriginal
    - write to it a hex that queries a condition
        - "never set foot here again, lest ye be exploded"
        - no spells allowed! can't use media maybe?
            - add a whitelist for raycasts or similar
        - queries every n ticks (configgable)
    - when that condition returns false, cast
        - could either have the victim on the stack,
        - or simply cast as them. dastardly!
    - both hexes are shown on the item
        - but who ever reads the fine print? ;)
    - can be used to invalidate other treatises
        - needs some pattern to do so, needing some reference

## compat
- Moves the Mind integration
    - adds that player to your list of controllable players
        - bid them to jump, punch, look, and use, etc.
            - that last thing is a little scary!
            - but your frenemy might not realize...
- Hexal & wisps
    - Special treatise: Wisp Writ
        - lower permission level
        - allows linking with someone's wisps, 
        - or consuming them at a normal cost
        - Manager's Purification, etc.
- Heirophantic Minds
    - be able to see minds?
    - "let me poke your brain"
        - trigger embedded minds manually?