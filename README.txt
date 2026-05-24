Upload these files to the root of your GitHub repo:

site.webmanifest
icon-32.png
icon-180.png
icon-192.png
icon-512.png
icon-1024.PNG

Then make sure your index.html <head> includes:

<link rel="manifest" href="site.webmanifest">
<link rel="apple-touch-icon" href="icon-180.png">
<link rel="icon" href="icon-32.png">
<meta name="theme-color" content="#0f1115">
