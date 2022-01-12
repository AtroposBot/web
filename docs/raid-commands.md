# Raid Commands

!!! tip "Arguments Legend"

    Command arguments surrounded by angle brackets `<>` are required. Arguments surrounded by square brackets `[]` are optional. Pipes `|` mean ` OR `.

??? info "/prune <number\>"

    This command will remove the specified number of recent messages in a channel.

    <number\> is the number of recent messages to remove in the channel.

??? info "/removesince <type\> <duration\>"

    This command will kick or ban all new players that have joined within the specified duration. 
    This is especially useful for slow join-spam raids or if the automatic join-spam moderation utility is disabled.
    The maximum duration is 2 days or 48 hours.

    <type\> is whether to kick or ban recent joins.

    <duration\> is what how long ago to remove users that have joined

??? info "/stopjoins <enable|disable\>"

    This will enable or disable the `stopjoins` utility, which when enabled will kick any joins with the following message:
    
    > You have been kicked from {guild name} at this time, as a part of anti-raid measures. If you aren't a spam-bot, please try again later!
    

