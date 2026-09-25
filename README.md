# Perceptrum Research — mr-perceptrum.com

Static site source for Perceptrum Research (FINALWEBSITE CONCEPT).

## Go live on mr-perceptrum.com

1. Add `index.html` (the concept HTML renamed) to this repo on `main`.
2. GitHub → Settings → Pages → Deploy from branch `main` / root.
3. Custom domain: `mr-perceptrum.com` (CNAME file is already set).
4. At the domain registrar, add:

```
A      @     185.199.108.153
A      @     185.199.109.153
A      @     185.199.110.153
A      @     185.199.111.153
CNAME  www   hrinsightverity-ctrl.github.io
```

Or connect this repo in Vercel and attach `mr-perceptrum.com` there, then use the DNS records Vercel displays.
