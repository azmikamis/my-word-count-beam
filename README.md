# my-word-count-beam

mvn compile exec:java -Dexec.mainClass=org.apache.beam.examples.KafkaWordCount -Dexec.args="--inputFile=pom.xml --output=kafcnts" -Pdirect-runner
