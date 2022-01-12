# Setup

Once Eris joins your guild, there are a few things you should take care of!

## Grant Required Permissions

If you try to use Eris without any permissions, you'll receive an embed 
notifying you of the permissions Eris needs and why. The list is as follows: 

```diff
+ View Channels
+ Manage Channels
+ Manage Roles
--- I need these to mute people and see chat
+ View Audit Log
--- I need this to log who does what
+ Manage Members
--- I need this to mute people and correct nickname hoists
+ Kick Members
+ Ban Members
--- I need these to kick and ban
+ Send Messages
+ Use External Emoji
--- I need these to log and interact with mods
+ Manage Messages
+ Read Message History
--- I need these to moderate chat
+ Mute Members
--- I need this to mute people
```

Additionally, please set Eris' highest role to be above anyone it may need to 
punish in the role hierarchy. Eris will only allow users with punishment 
permission to punish those lower than they are in the role hierarchy.

!!! warning "Eris will not function as intended without having all required permissions"

    This is so that there are no errors in executing commands.

## Set ModMail Channel

Use `/settings modmail set` in your preferred internal staff channel. 
This will not only enable the `/modmail` command for people in your server, 
it will also tell Eris where to send system messages to mods. For example, if a 
user is auto-muted due to a suspicious link, Eris will post it for review in 
the mod mail channel.

## Set Logging Channels

Use `/settings log info` to read about the various logging types and how to 
set them in your guild.  

## Set Anti-Spam Thresholds

Use `/settings antispam info` to see the default anti-spam values and use 
`/settings antispam set` to set or modify one or more of the listed options.

## Set Muted Role

If you have a role you're already using as a 'muted' role, that prevents 
certain actions like speaking and reacting in channels, use `/settings 
mutedrole set <role>` to set it as the role Eris will apply to people when you 
mute them using Eris. If you do not have one or would prefer Eris to 
programmatically create one for all channels (voice and text), simply mute 
someone and Eris will handle the rest.