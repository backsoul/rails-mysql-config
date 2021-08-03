# rails-mysql-config

# MySQL.  Versions rails 6.
#
# Install the MySQL driver:
#   gem install mysql2
```
development:
  adapter: mysql2
  encoding: utf8
  reconnect: false
  database: rails_notes
  pool: 5
  username: root
  password: password
  host: localhost

test:
  adapter: mysql2
  encoding: utf8
  reconnect: false
  database: GoSlow_test
  pool: 5
  username: root
  password:
  host: localhost

production:
  adapter: mysql2
  encoding: utf8
  reconnect: false
  database: GoSlow_production
  pool: 5
  username: root
  password: production
  
  host: localhost
  
```

