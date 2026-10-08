# Troubleshooting

## No mail or parcels

Check whether the same information appears in your own PostNL account. Then verify that the correct My PostNL device is selected. If needed, run **Synchronize PostNL** through a Flow and check **Last update** and **Connection status**.

## Sign-in expired

Open **Repair** on the affected device and sign in again with your PostNL account. Follow the sign-in steps to restore the connection.

## Older mail is missing from My Post

The widget shows the current live mail list. The 21-day local retention period does not mean all old items remain in this widget. Mail counts and expected-mail values focus on current mail.

## Missing window, image or parcel journey

These features depend on data supplied by PostNL. The journey widget requires an undelivered parcel with status events. The app cannot create a missing mail scan.

## No immediate notification after installation

The first successful synchronization establishes a baseline. Triggers then fire for newly detected items or changes. The app normally schedules synchronization every five minutes; this is not a continuous push connection to PostNL.

## Ask for help

Include your app version, Homey version, affected widget or Flow and expected behaviour. Remove addresses, barcodes, mail scans and sign-in details from public screenshots.

[Community support](https://community.homey.app/t/app-pro-postnl-for-homey/159674)
