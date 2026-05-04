# Wild Salmon — Developer Site

Official developer website for the **Wild Salmon** Android game (`com.wildsalmon.neonbird`).

This repository is deployed via **GitHub Pages** and hosts:

- `index.html` — developer landing page
- `privacy.html` — privacy policy
- `app-ads.txt` — AdMob / IAB Tech Lab authorization file

## AdMob verification

`app-ads.txt` contains the publisher authorization line required by Google AdMob:

```
google.com, pub-1202818263280891, DIRECT, f08c47fec0942fa0
```

After GitHub Pages is enabled, the file must be reachable at:

```
https://<username>.github.io/app-ads.txt
```

This exact URL (without `/app-ads.txt`) must also be set as the **Developer Website** in Google Play Console → *Store listing* → *Store settings*.
