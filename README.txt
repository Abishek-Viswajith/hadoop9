wget https://dlcdn.apache.org/spark/spark-3.5.5/spark-3.5.5-bin-hadoop3.tgz

tar xvf spark-3.5.5-bin-hadoop3.tgz

sudo mv spark-3.5.5-bin-hadoop3 /opt/spark

nano ~/.bashrc

export SPARK_HOME=/opt/spark
export PATH=$SPARK_HOME/bin:$PATH

source ~/.bashrc

spark-shell

pyspark

sc.pythonVer

sc.master

my_list = range(1,10)
squared_list_lambda = list(map(lambda x: x**2, my_list))

print("The squared numbers are", squared_list_lambda)
