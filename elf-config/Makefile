elf: elf-up elf-test elf-tidy

elf-up:
	./elf.sh

elf-test:
	curl localhost/elf

elf-tidy:
	rm -rf elf-config

elf-down:
	helm uninstall elasticsearch --namespace=elf
	helm uninstall fluent-bit --namespace=elf
	helm uninstall kibana --namespace=elf
	kubectl delete random-logger -n elf
