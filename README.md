#Propeller

a prop and costume lending/rental tracking database application for a small theater or rental house.  Initially made for Fir Acres Theater at Lewis & Clark College.

##Roadmap

###Users
Props/Costumes Manager
can:
- maintain inventory
- add photos
- input notes
- add tags
- update condition
- check items out to renters

Renter
can:
- view inventory
- check availability,
- view condition,
- add to their cart
- request items in cart
- report something as broken
- report something as damaged
- see a list of what they are responsible for replacing
- see a dollar value of what they owe for damage

###Items
Prop   
has:
- name
- description
- photo(s)
- condition (new/good/fair/disrepair/broken)
- date expected back
- current location (visible only to the props manager)
- storage location (visible only to the props manager)

Costumes   
has:
{repeat: prop}
- time period

###System
generates and keeps record of:  
- renters' agreements
- renters' contact info
- renters' responsibilities to the theater (returns/replacements/fees)
