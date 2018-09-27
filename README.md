##
1. Start the client.
2. Click "Fingerprint" and enter your pixelcanvas.io fingerprint.
3. Add your templates into the "Templates" view. Activate templates by checking their checkbox. (If you haven't done that already)
4. Let the client do the work until a message requester with the title "Captcha" pops up. You then have to use the pixelcanvas.io website and place a pixel which causes a recaptcha to appear. Solve the captcha(s), click "OK" on the requester, and the bot will work for another hour.

## Known problems (Which also may never be fixed)
- If you zoom out and press "Load Viewport" the client may hit the process handle limit, as this will create a lot of small images.
  This could be fixed by caching or using bigger image chunks.
  (But meh, just don't let it load 10000 images ;) )
- Most network communication is blocking (Except chunk downloading). But that shouldn't cause any troubles.
- Estimations and pixelrates are wrong after starting the client, but they will show correct values after 30 placed pixels.
- There is probably more small stuff, but the client does its job.

## Screenshots
A client running for a month:
![<Image missing>](/Screenshots/V0.946.png)
