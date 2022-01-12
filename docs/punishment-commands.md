# Punishment Commands

!!! tip "Arguments Legend"

    Command arguments surrounded by angle brackets `<>` are required. Arguments surrounded by square brackets `[]` are optional

??? info "/ban <user> \[reason] \[duration] \[days] \[dm]"

    This command will ban the user and log it for future reference, optionally notifying the user of the reason for their ban.    

    <user\> is a valid user. A mention or ID works and the user does not need to be in the server.

    [reason] is the optional punishment reason.

    [duration] is how long the punishment should apply. For a permanent punishment, do not add a duration. 

    > Duration format is `1mo2w3d4h5m` for 1 month, 2 weeks, 3 days, 4 hours, 5 minutes.

    [days] is the number of days of messages to delete. Can be 1-7 and is 0 if ommitted.

    [dm] is a boolean to attempt to notify the user of their punishment. Defaults to true.

??? info "/kick <user> \[reason] \[dm]"

    This command will kick the user and log it for future reference, optionally notifying the user of the reason for their kick.
    
    <user\> is a valid user. A mention or ID works and the user needs to be in the server.

    [reason] is the optional punishment reason.

    [dm] is a boolean to attempt to notify the user of their punishment. Defaults to true.

??? info "/mute <user> \[reason] \[duration] \[dm]"

    This command will mute the user by applying a 'muted' role to them, and logging it for future reference, optionally notifying the user of the reason for their mute.
    
    <user\> is a valid user. A mention or ID works and the user needs to be in the server.

    [reason] is the optional punishment reason.

    [duration] is how long the punishment should apply. For a permanent punishment, do not add a duration. 

    > Duration format is `1mo2w3d4h5m` for 1 month, 2 weeks, 3 days, 4 hours, 5 minutes.

    [dm] is a boolean to attempt to notify the user of their punishment. Defaults to true.


??? info "/warn <user> \[reason] \[dm]"

    This command will warn the user and log it for future reference, optionally notifying the user of the reason for their warn.
    
    <user\> is a valid user. A mention or ID works and the user needs to be in the server.

    [reason] is the optional punishment reason.

    [dm] is a boolean to attempt to notify the user of their punishment. Defaults to true.


??? info "/note <user> \[reason]"

    This command will log a note on the user for future reference, and will never notify the user.
    
    <user\> is a valid user. A mention or ID works and the user needs to be in the server.

    [reason] is the optional punishment reason.


