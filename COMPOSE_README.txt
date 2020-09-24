.env needs to be populated with the appropriate vairables.

DISCORD_BOT_TOKEN needs your discord bot token
ACME_EMAIL is your email address used to pull certificates from Let's Encrypt
DOMAIN_NAME is the domain you will be hosting your server at, Let's Encrypt will generate the certs for this
AUTH_STRING is a .htaccess style authentication string used to access your Traefik Dashboard if desired

Server needs to have exposed ports 443 (for the Let's Encrypt TLS Challenge and optional Traefik dashboard) and ports 8124