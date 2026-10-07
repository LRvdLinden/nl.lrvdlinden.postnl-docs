# Flow cards

Use the cards belonging to the correct My PostNL device. A trigger supplies data for the event that starts the Flow.

![PostNL Flow cards in English](<.gitbook/assets/flow-cards (1).png>)

## When…

* New mail is expected
* A new parcel was found
* A delivery window became available
* A parcel status changed
* PostNL synchronization failed
* The PostNL login expired

## And…

* Mail is expected
* Parcels are underway
* A delivery window is known

## Then…

* Synchronize PostNL

## What happens when a delivery window changes?

**A delivery window became available** fires when an undelivered parcel first receives a window. A change to an existing window or delivery date is handled by **A parcel status changed** when the app detects that change in the received data. Use the status card to notify users about shifts as well.

[Flow tokens](tokens.md) · [Examples](examples.md)
