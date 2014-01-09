staging_buildout
================


# update all remote repositories
bin/develop up -v

# see processes
bin/supervisorctl status

# restart
bin/supervisorctl restart fika
