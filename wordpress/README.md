# Wordpress
Worpress installation, including database and connection to "jwilder/nginx-proxy" and "jrcs/letsencrypt-nginx-proxy-companion"

Ports:
${HOST_PORT}: The port on the host on which the site will be accessible
   
Website
${SITE_NAME}: Site name (lowercase without spaces)

${SITE_URL}: Site URL (without subdomain. A naked and a "www" subdomain entry is added automatically)

Database
${DATABASE_PASSWORD}: You normally won't have to manually enter this anywhere, so make it complex

${MYSQL_ROOT_PASSWORD}: You normally won't have to manually enter this anywhere, so make it complex and different from the database password

Reverse Proxy and Let's Encrypt
${REVERSE_PROXY_LETSENCRYPT_ENABLED}: Use a single space (" ") for enabled, and a hashtag ("#") for disabled

${REVERSE-PROXY_NETWORK}: The external Docker network the reverse proxy runs on

${REVERSE-PROXY_NETWORK}: The external Docker network the reverse proxy runs on

${LETSENCRYPT_EMAIL}: The email address to use with Let's Encrypt
