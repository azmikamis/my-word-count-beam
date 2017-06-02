# my-word-count-beam

mvn compile exec:java -Dexec.mainClass=org.apache.beam.examples.KafkaWordCount -Dexec.args="--inputFile=pom.xml --output=kafcnts" -Pdirect-runner

bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic test

bin/kafka-console-producer.sh --broker-list localhost:9092 --topic test
