sudo apt install openjdk-11-jdk scala curl mlocate

curl -O https://archive.apache.org/dist/spark/spark-3.1.1/spark-3.1.1-bin-hadoop3.2.tgz

tar xvf spark-3.1.1-bin-hadoop3.2.tgz 

sudo mv spark-3.1.1-bin-hadoop3.2/ /opt/spark 

nano ~/.bashrc
-- Add at end of line
  * export SPARK_HOME=/opt/spark
  * export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin

source ~/.bashrc

start-master.sh or start-master.sh --port 7072 --webui-port 8082

sudo ss -tunelp | grep 8080

http://localhost:8080/

start-slave.sh spark://ubuntu:7077

sudo updatedb

locate start-slave.sh

/opt/spark/bin/spark-shell or /opt/spark/bin/pyspark

Shuddown

stop-slave.sh

stop-master.sh 

stop-all.sh

start-all.sh




