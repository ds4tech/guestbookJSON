go-webservice-sample
====================

Sample implementation of a web service in Go using Martini.

go run client.go --request_url=http://127.0.0.1:3000/guestbook --request_method=post --request_data={"Id":0,"Email":"EMAIL","Title":"TITLE","Content":"CONTENT"}

curl -H Content-Type: application/json -d {"Id":1,"Email":"ds4tech@gmail.com","Title":"Mateusz","Content":"testuje nadal JSON"} http://127.0.0.1:3000/guestbook

