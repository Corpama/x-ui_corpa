# x-ui_corpa_edition

This is a x-ui modified version, It's add some features.

1. reset all inbounds traffic.
2. an email record of every inbound, you can write a script retrieve these email records(from database) to notify invalid users.
3. this version of x-ui must used with nginx, the traffic will transfer through the nginx's proxy and the inbound stream must be websocket(ws)

Test before use, even i had test it.

### Development schedule

1.Multi server control,plan to split project into master and child. Administrator  just need alter users config on master server,and the altered config will sync to child nodes. And expiry time will be synced too.
