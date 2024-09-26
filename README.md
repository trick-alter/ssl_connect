# ssl_connect
java ssl connect

```bash
javac -d . HttpsClient.java
jar cvfeP ssl_connect.jar ssl_client.HttpsClient -C . ssl_client/
export URL=https://some_site:8443; java -jar ssl_connect.jar
```
