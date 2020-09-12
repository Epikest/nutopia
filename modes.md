---
layout: default
title: Modes
description: The possible modes a user/channel may have!
---

# Modes

Modes distinguish specific users or channels, and help tell what they're for or what powers they posses.
Each user and channel mode are listed below.

## User Modes

User modes grant users specific perms or designate a status or perk. 
You can view your user modes at any time with `;umode`.

| Mode | Description                                                                                  |
| ---- | -------------------------------------------------------------------------------------------- |
| +B   | Bots                                                                                         |
| +Q   | Quieted User. (Revokes "Send Message" Permission)                                            |
| +k   | This user is a god, they cannot be kicked or set -qaohv. (Grants "Administrator" permission) |
| +d   | Marks this user as a donor.                                                                  |
| +m   | Gives this user access to #music, given to any members of the Music Room voice channel.      |
| +e   | Gives the user access to external emotes                                                     |
| +w   | Gives the user ability to modify webhooks.                                                   |
| +n   | Hides "unimportant" channels (any with +M set but without +i set)                            |
| +r   | Gives the user access to Manage Roles                                                        |
| +b   | Designates user as a "Server Booster"                                                        |

## Channel Modes

Channel modes mark specific things about a channel.
These are listed in the channel's topic inside [brackets].

| Mode | Description                                                     |
| ---- | --------------------------------------------------------------- |
| +n   | No External Messages (Webhooks)                                 |
| +t   | Only users with +Yqaoh may change the topic                     |
| +i   | Marks channel as "important" and cannot be hidden with umode +n |
| +m   | Only users with half-op or more can speak                       |
| +M   | Only NetAdmins may speak.                                       |
| +p   | Channel must be manually joined via ;join                       |
| +s   | Channel is top secret and people must be added manually         |

<script>
$('table').addClass('table table-striped table-bordered table-hover');
$('thead').addClass('thead-dark');
</script>