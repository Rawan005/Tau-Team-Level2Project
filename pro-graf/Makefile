pro-graf:  pro-graf-up pro-graf-test pro-graf-tidy

pro-graf-up:
	./pro-graf.sh

pro-graf-test:
	curl localhost/grafana

pro-graf-tidy:
	rm -rf pro-graf

pro-graf-down:
	helm uninstall prometheus-operator -n monitor
