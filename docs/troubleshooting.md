# Troubleshooting

## Connectivity (Bluetooth, wearables, or notifications)
from Roman and silentace07 on discord
Make sure to look at the Duraspeed settings in your Android Settings app. Duraspeed will kill processes in order to keep apps in the foreground more performative, and allow battery optimizations. Although this can be helpful, it can also impact your user experience.

In the settings you are able to fully disable Duraspeed, or whitelist particular apps if you prefer.

## Apps Not Displaying Correctly
### Due to Screen Size
from user lucibugt on discord

There are quite a few apps that do not show properly with this screen. Luckly for all I needed so far, its only the onboarding screen that cuts out. So to pass the initial setup for Oura, NissanMessagePark or SMBC  bank I enabled developer mode connected to my pc and changed the resolution to 600x1000 with adb shell wm size 600x1000. Complete the setup, put back the resolution, disable dev and good to go.