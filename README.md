# MCLeaksUUIDs
List of UUIDs from MCLeaks alts accounts.

You can use this list to blacklist those users on your minecraft server

# How to generate list

1) Go to https://mcleaks.net/get and generate Token (it may be JAVA APP)

2) POST Token via small JAVA APP to http://auth.mcleaks.net/v1/redeem and get nickname from response:
```JSON
{"success":true,"result":{"mcname":"V0dk4_LimaoSeco","session":"EuHGFfpWciA8kiBOkSyzGaV7701xjcpYG6Ell3hymSGGbhvva45Qe1Yl10TlcijS"}}
```

3) Convert nickname from response to UUID using Mojang API
```JSON
bd52224a37bb48909ae317ae8bdea897
```
