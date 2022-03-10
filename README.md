# Discord-MMO-Strategy-Server-Template

## Role Management 101

The server has the following roles:

**Note**: Roles are hierarchical. For example, someone with both Elite-R5 and Council-R5 role will be identified as Elite-R5. 

**Server based**:
- Discord Server Owner: Owner with all rights to all channels
- King: Able to post Game Server Rules to the server-rules channel. No other permissions. Must be assigned in addition to other roles.
- Server-Admin: Internal administrator; Can be granted most permissions, almost as same as owner. Cannot see any private categories or channels except this user-guide,
- Member: All members of the server. Preferably assigned role by a bot.

**Elite Teams Only (Top tier)**:
- Elite-Unlock: User with discord knowledge from top tier teams. Can only view public channels. Can assign roles to other Elite roles.
- Elite-R5: R5 with access to elite-r5-chat channel, in addition to others
- Elite-Leadership: All R4s and R5s of top tier teams.

**Council Teams Only (Top teams with NAP; includes all elite members)**:
- Council-Unlock: User with discord knowledge from top tier teams. Can only view public channels. Can assign roles to other Council roles.
- Council-R5: R5 with access to council-r5-chat  channel, in addition to others
- Council-Leadership: All R4s and R5s of NAP teams.

**General**:
- Server-Unlock: User with discord knowledge from entire server. Can only view public channels. Can only assign roles to other non NAP  roles.
- Server-R5: All R5s in discord with access to r5-chat channel, in addition to others
- Server-Leadership: All R4s and R5s in the server 

## Roles Workflow

1. User accepts invite and is assigned the Member role. Can only view public categories.
2. Mee6 bot sends a welcome message in the channel and as a PM.
3. Someone with admin or unlock roles assigns applicable role for leaders.
   Important: Assign all applicable roles.
4. People with relevant roles can view applicable channels or categories.

**Permissions Notes**:
- Never assign permission directly to a user. Always assign roles.
- Assign all applicable roles. However, you can only assign someone a role lower than yours.
- Always create private categories, and assign roles to categories. Only some categories are public.
- Add Translation bot as a member to any new role.
- Add roles to categories, when applicable, and sub-channels inherit those roles. However, you can also modify the roles for specific channels. 

## Role Matrix

![vivaldi_RKcl5HFccP](https://user-images.githubusercontent.com/54368406/157570725-8defe47c-5a86-4426-851f-f2d3a902e6d9.png)
