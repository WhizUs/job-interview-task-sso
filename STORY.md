# The Story

## WhizAuth Corp

Another day another issue. Bob (the only DevSecOps guy at his place) gets an urgent call from Tom in the morning:

> Tom: dude we are now live with our new app we've been working for years, I guess you remember, but it seems to be the case that somehow we missed to add this login stuff

> Bob: ok?

> Tom: could you somehow fix this? Some secure temporary solution integrated into the Corp's SSO system would be totally sufficient.

> Bob: well...

> Tom: ah yeah, the app is currently open to the net so we would need to move it behind the login thingy. No direct ingress pls.

> Bob: ok

Bob remembers all these legacy apps he had some kind of same issues in the past. 

> Was it [oauth2-proxy](https://oauth2-proxy.github.io/oauth2-proxy/) we used then? Or something newer, like [pomerium](https://www.pomerium.com/)? I even remember there was something with the [keycloak-gatekeeper](https://github.com/oneconcern/keycloak-gatekeeper), but wasn't it discontinued? Never mind, let's configure another one.

## The App

Bob writes down his steps he is going to perform:

1. Register and configure a new client within the SSO platform
2. Prepare the auth proxy with the proper values
3. Move the app to the internal network
4. Test with Corp Login

Bob remembers that those days in the past he closely worked with Alice on that topics. She will definitelly remember if he stucks on some point.

Bob decides to call Alice...