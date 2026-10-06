# Flow examples

## Notify about new mail

**When:** New mail is expected.  
**Then:** use a Homey notification action: “[Number of mail items] new mail items were found.”

Optionally use **Mail item image** with an image-capable action when **Image available** is true.

## Announce a delivery window

**When:** A delivery window became available.  
**Then:** send: “Your parcel from [Sender] is expected on [Delivery date], between [Delivery window from] and [Delivery window to].”

## Updated delivery information

**When:** A parcel status changed.  
**Then:** send: “[Sender]: [Official PostNL status]. Expected: [Delivery date] [Delivery window].”

This Flow can also fire when the date or window changes without a change to the status text. Not every parcel has all fields.

## Restore sign-in

**When:** The PostNL login expired.  
**Then:** notify yourself to repair the affected My PostNL device.

Notification actions are supplied by Homey or another installed app. Insert tokens using the token picker; square brackets above are explanatory.
