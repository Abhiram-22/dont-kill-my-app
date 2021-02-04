---
name: Vivo
manufacturer:
  - vivo
award: 3
position: 10
redirect_from: /vendors/vivo.html
explanation: "
Basically, For the apps to run in background(at all), They need a special permission called <strong>Autostart</strong>.
This might be turned on for all apps, mostly.
and then there is another thing called <strong>Battery Optimization</strong>. Even though the "AutoStart" is turned on for a given app, the app may eventually will get killed without you turning off the Battery optimization.

<strong>Conclusion</strong>:For a app to work as intended, you need to enable AutoStart and disable Battery Optimization.

"

user_solution: "

## Autostart

Based on the information by Vivo, this option should be present on all Vivo phones.<br>
Newer OS version: *Settings > More settings > Applications > Autostart* to turn on/off the app switch.<br>
For Funtouch OS 2.6 and lower version: *i Manager > App manager > Autostart manager* to turn on/off the app switch.

## Vivo Y91

### Lock the app in taskbar

Apps locked in the taskbar are safe from getting terminated when they run on the background.
<br>
1. Swipe up in your home screen while the app is open in background, and swipe the app icon <strong>down</strong>.
<br>
2. Tap the lock icon.
<br>
3. Done - now the app is locked in the taskbar.

<div class=\"img-block\">
  <figure>
    <img src=\"/assets/img/vivo/vivo_1.jpg\">
    <figcaption>1. Swipe up the app down <br> while it is open in the background.</figcaption>
  </figure>

  <figure>
    <img src=\"/assets/img/vivo/vivo_2.jpg\">
    <figcaption>2. Tap on the lock icon that appears.</figcaption>
  </figure>

  <figure>
    <img src=\"/assets/img/vivo/vivo_3.jpg\">
    <figcaption>3. App is locked.</figcaption>
  </figure>

</div>

### Allow the app to keep running even during high power consumption

<br>
1. Go to system Settings > Battery.
<br>
2. Go to High background power consumption.
<br>
3. Find your app in the list and enable the high battery consumption.

<div class=\"img-block\">
  <figure>
    <img src=\"/assets/img/vivo/vivo_4.jpg\">
    <figcaption>1. Open Battery section.</figcaption>
  </figure>

  <figure>
    <img src=\"/assets/img/vivo/vivo_5.jpg\">
    <figcaption>2. Go to High background power consuption.</figcaption>
  </figure>

  <figure>
    <img src=\"/assets/img/vivo/vivo_6.jpg\">
    <figcaption>3. Enable for your app.</figcaption>
  </figure>

</div>


"

developer_solution: "No known solution on dev end yet."

---
