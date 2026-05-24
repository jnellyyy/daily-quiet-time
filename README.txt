Upload all files to the same root folder as index.html.

Important:
favicon.ico helps browser tabs.
icon-180.png helps iPhone Add to Home Screen.
site.webmanifest helps Android Install app.

Add this to the index.html head:

<link rel="manifest" href="./site.webmanifest?v=5">
<link rel="apple-touch-icon" sizes="180x180" href="./icon-180.png?v=5">
<link rel="icon" href="./favicon.ico?v=5" sizes="any">
<link rel="icon" type="image/png" sizes="32x32" href="./icon-32.png?v=5">
<link rel="icon" type="image/png" sizes="192x192" href="./icon-192.png?v=5">
<meta name="theme-color" content="#0f1115">
