#
IMAGE := version_0
PORT := 8099

help:
	@echo Add help here


.PHONY: build
build:
	@docker build -t $(IMAGE) .

.PHONY: run
run:
	docker run --rm -p $(PORT):$(PORT) $(IMAGE)
