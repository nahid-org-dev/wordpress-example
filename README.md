## Sample Wordpress
####
### Run in KloverCloud
- Make sure you already have a MySQL Server Running & create a Database in your MySQL Server
- Create a fork/clone of this repository in your git account
- Create new app by On-boarding from Git in klovercloud
- Select PHP as language and LARAVEL as the framework
- Select atleast 1 vCPU & 2GB RAM
- Select atleast 10GB Persistent Volume (Mount directory: /var/www/html)
- Create Application
- Set the following the Environment Variables\
`SITE_URL` (Initially you can set the Default External Access Url here including 'https://' at the beginning or you can also set your personal domain also)\
`DB_HOST` (DB Service Endpoint of your MySQL Database Server)\
`DB_USERNAME` (Your Database Username)\
`DB_PASSWORD` (Your Database Password)\
`DB_NAME` (Your Database Name)
- Build & Deploy
- Enjoy
