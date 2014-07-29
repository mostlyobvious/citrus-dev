kafka_server:   kafka-server-start.sh /usr/local/etc/kafka/server.properties
kafka_consumer: kafka-console-consumer.sh --zookeeper localhost:2181 --topic citrus_stream
builder:        bash -c "sleep 1; BUNDLE_GEMFILE=citrus-builder/Gemfile bundle exec ./citrus-builder/bin/citrus-builder"
