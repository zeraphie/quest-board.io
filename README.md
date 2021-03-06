# Quest Board.io
A calendar web app for discord for groups/planning/organisation. Below is a list of what will be happening in each phase of this project. This is planned to be an open source project under the MIT Licence.

*Note: This readme is currently a live document, it can change quite a lot until I get started on this!*

*Note 2: If you want to suggest something, add it to* [this issue](/../../issues/1)

## Phase 0 - Name
- [x] Figure out a new name for this, as unable to use discord in the app name due to TOS *Naming this Quest Board.io`

## Phase 1 - MVP (Minimum Viable Product)
- **Backend**
  - [x] Grab a domain name - `quest-board.io`
  - [ ] Create a droplet on Digital Ocean dedicated to this
  - [ ] Choose the type of server for it (caddy? nginx?)
- **Frontend**
  - [ ] Choose a general aesthetic (discord style?)
  - [ ] Choose a framework/library (most likely react)
  - [ ] Hot module reloading (not needed but very useful)
  - [ ] Choose/design a calendar
    - [ ] Perhaps [this](https://codepen.io/zephyr/pen/zKAPrG)? (without jQuery) 
    - [ ] Should fill the screen as it is main focal point of app
    - [ ] Should be able to assign multiple timeranges per day without overlapping
- **Users**
  - [ ] A user can login using their discord account
  - **Calendar**
    - [ ] A user can edit their calendar with times they are available
- **Groups**
  - [ ] Created by a user (who is designated the Leader of the group)
  - [ ] Has basic information (i.e. name, game, link)
  - [ ] Leader can invite a user to a group
  - [ ] Leader can kick a user from a group
  - [ ] Add timeslot to the calendar that propagates to each member of the group's calendar
  - **Calendar**
    - [ ] A group calendar highlights times that are available
    - [ ] A group calendar lists users who aren't available at a timeslot

## Phase 2 - Discoverability & Customisations
- **Discord Server**
  - [ ] Create a discord server for the app
- **Users**
  - [ ] A user can edit a calender with times they are not available
  - [ ] A user can designate the type of availability for a timeslot
  - [ ] A user can add their general availability (like if they work regular hours etc)
    - [ ] Repeat events with control on times of day, and days in week
    - [ ] Overwritable by adding a timeslot
  - [ ] A user can customise their experience
    - [ ] Editable Dashboard
    - [ ] Different themes for the app
- **Groups**
  - [ ] The leader can set whether the group is discoverable
    - [ ] A discoverable group can be searched for by any user
  - [ ] The leader can make other people the lead of the group
  - [ ] Discord integration
    - [ ] Generate invite link
    - [ ] See whose online
  
## Phase 3 - Discord Bot
- **Bot**
  - [ ] Create a discord bot
  - [ ] Link to the web app
  - [ ] Help info
  - [ ] Notification to group Leader if someone changes their availability soon before the assigned group time
  - [ ] Get group's current calendar
  
## Phase 4 - Extended User Profile (separate app)
- **Extended User Profile**
  - [ ] A user can add the games they play
    - [ ] A user can add the characters they play to a game
    - [ ] Characters also have a profile with more in depth information
    - [ ] A user can designate a character to a group
  - [ ] A user can add themselves to a discoverable group
  - [ ] A user can remove themselves from a discoverable group

## Phase 5 - Integrations (3rd party software)
- **Integrations**
  - [ ] Integration with Google Calendar for import/sync for availabilities
  - [ ] Discord Rich Presence?
