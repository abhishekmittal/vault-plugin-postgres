#0.1.6
 - Remove *sql.DB resource caching and create fresh connections when needed
 
# 0.1.5
 - metadata: Added new metadata path to associate arbitrary key-value data
   with clusters and databases.

# 0.1.4
 - cluster/list: Added the path to list all registered clusters
 - database/list: Added the path to list all registered databases in a cluster

# 0.1.3
 - cluster/update: New cluster registration generates a random name for management user
 - database/update: New database registration generates a random name for objects owner
 - database/update: New option `create_db` can be used to disable new database creation when database is registered for
   the first time. This option can be used to migrate existing databases to this plugin backend.