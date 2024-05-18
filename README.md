# adityagaur0-cloudflare_vercel_customdaomain
1. Go to GoDaddy Buy ur domain -> then go to cloudflare -> setup cloudflare -> then open godaddy -> open ur domain portfolio ->go to dns ->nameserver ->add cloudflare nameserver to custom nameserver.
2. Host ur project on vercel. -> Go to domain -> custom domain ->save cname and a name and their target.
3. Go to cloudflare . delete the existing A and Cname to vercel A and cname. 

```
ref
Add CNAME Records:

1. Root Domain (@):
  Click on Add Record.
  Type: CNAME
  Name: @
  Target: your-project.vercel.app
  TTL: Auto
  Proxy status: DNS Only (change to Proxied after testing)
  Click Save

2. www Subdomain:
  Click on Add Record.
  Type: CNAME
  Name: www
  Target: your-project.vercel.app
  TTL: Auto
  Proxy status: DNS Only (change to Proxied after testing)
  Click Save
```

## DONE
