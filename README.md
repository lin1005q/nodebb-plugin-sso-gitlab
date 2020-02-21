# NodeBB OAuth SSO

NodeBB Plugin that allows users to login/register via Gitlab as OAuth provider.

## How to Adapt

1. Fork this plugin
    * ![](http://i.imgur.com/APWHJsa.png)
1. Create Oauth application in your gitlab instance    
1. Add the OAuth credentials to nodebb config.json (id, secret, authURL, tokenURL and userRoute)
1. Activate this plugin from the plugins page
1. Restart your NodeBB
1. Let NodeBB take care of the rest

