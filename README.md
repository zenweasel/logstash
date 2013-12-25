Logstash
========

Ansible roles for Logstash installation, with a minimal configuration: input from logfiles, output to Redis and to Elasticsearch.

Requirements
------------

Logstash need a JVM. For your peace this role include an installation of OpenJDK.

Role Variables
--------------

	logstash_url: "https://download.elasticsearch.org/logstash/logstash/logstash" # Logstash Download Url

	logstash_ver: "1.3.2"							      # Logstash Version	

Dependencies
------------

Suggested roles: bennojoy.redis - valentinogagliardi.rsyslog-server

License
-------

BSD

Author Information
------------------

Valentino Gagliardi - valentino.g [at] servermanaged.it

