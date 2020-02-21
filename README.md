# NodeBB OAuth SSO

NodeBB Plugin that allows users to login/register via Gitlab as OAuth provider.

## How to use?

1. npm install nodebb-plugin-sso-gitlab
1. Create an Oauth application in your gitlab instance (Callback URL -> http(s)://<your-nodebb-url>/auth/gitlab/callback)   
1. Add OAuth credentials to nodebb config.json (id, secret, authURL, tokenURL and userRoute)
⋅⋅* authURL -> http(s)://<your-gitlab-instance-url>/oauth/authorize
⋅⋅* tokenURL -> http(s)://<your-gitlab-instance-url>/oauth/token
..* userRoute -> http(s)://<your-gitlab-instance-url>/api/v4/user
1. Activate this plugin from the plugins page
1. Restart your NodeBB
