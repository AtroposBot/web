# Search Commands

!!! tip "Arguments Legend"

    Command arguments surrounded by angle brackets `<>` are required. Arguments surrounded by square brackets `[]` are optional. Pipes `|` mean ` OR `.

## Audit

??? info "/audit recent"

    This command will display recent command usages in a guild.

??? info "/audit id <number\>"

    This command will display information for a specific command usage by its ID number.

??? info "/audit user <snowflake|mention\>"

    This command will display information for command usages by a user.

    <mention\> can be a valid user mention or ID, but will not work for deleted users.

    <snowflake\> will search by a user ID snowflake, which will work for deleted users.

## Cases

??? info "/case search recent \[type]"

    This command will display recent punishment cases in a guild.
    
    \[type] will filter the results by the selected type: ban, kick, mute, warn, or note.

??? info "/case search user <snowflake|mention\>"

    This command will display punishment cases for a user in a guild.
    
    <mention\> can be a valid user mention or ID, but will not work for deleted users.

    <snowflake\> will search by a user ID snowflake, which will work for deleted users.

??? info "/case search id <caseid\>"

    This command will display information for a specific case by its ID.

    <caseid\> is the case number of a punishment to search for details on.