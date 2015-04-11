---
title: Environment Variables
---

# Environment Variables

Divshot's development, staging, and production environments are great for operations, but don't solve the problem of service configurations. Environment variables are a great way to specify API keys for 3rd party services.

Be careful not to set any secret keys as environment variables, as this data will be accessible to your users. An appropriate use case for environment variables would be analytics tracking codes.

##Adding Environment Variables to Your App


```bash
divshot -c divshot-dev.json env development env:add development KEY1=value1 KEY2=value2
divshot -c divshot-staging.json env staging env:add staging KEY1=value1 KEY2=value2
divshot -c divshot-prod.json env production env:add production KEY1=value1 KEY2=value2
```

##Current environment 

There variables are set on all environments and stored in `/__/env.js`

```bash
MIXPANEL_TOKEN
GOOGLE_UA
```



###More info

More info can be found here [I'm an inline-style link](http://docs.divshot.com/guides/environment-variables)
