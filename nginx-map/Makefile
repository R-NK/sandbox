:PHONY bot
bot:
	curl -A "Bot" -LI localhost:8080 -o /dev/null -w '%{http_code}\n' -s

ok:
	curl -LI localhost:8080 -o /dev/null -w '%{http_code}\n' -s