# Nimbus-configuration-key-value-pair-missing
Nimbus configuration , key value pair missing

My problem is I am not able to see Nimbus configuration in Storm UI. The key values are missing. I have upgraded storm from 0.8 to 0.9.3 version. I am able to connect to UI , no problems but i am not able to see the Nimbus configs at all. The key values are missing. Attached is the UI capture and storm.yaml file.  storm.zookeeper.servers:
     - "X.X.X.X"
     nimbus.host: "X.X.X.X"
     nimbus.childopts: "-Xmx1024m -Djava.net.preferIPv4Stack=true"
     ui.childopts: "-Xmx768m -Djava.net.preferIPv4Stack=true"
     supervisor.childopts: "-Djava.net.preferIPv4Stack=true"
     worker.childopts: "-Xmx768m -Djava.net.preferIPv4Stack=true"
     storm.local.dir: "/app/storm"

Versions storm 0.9.3 Kafka 0.8.2

