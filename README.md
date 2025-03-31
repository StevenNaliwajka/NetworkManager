# NetworkManager
 Has a few roles.

## Central registry 
- Json file or files for all known services
- Stores details about vlans, failover settings, upstream rules, settings.

## Toggleable settings to allow for dynamic.
-	Pfsense automation
- Cloudflare DNS automation, (includes failover control)
    - Failover control allows for health checks and re-routing the cloudflare dns entry.
      
## fastAPI server to allow for other machines to auto-register or query.
- Probably setup pubkey/priv key relation to enable approved querying,
