# A useful Makefile for generating and running the basic application.

default: clean create build run log

create:
	bacn create bacn-test com.strongloop.bacn-test BacnTest --template ionic

clean:
	rm -rf bacn-test

build:
	cd bacn-test; bacn build

run:
	cd bacn-test; bacn run

log:
	cd bacn-test; bacn log -f
