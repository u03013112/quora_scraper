TAG=v1
ACCOUNT=u03013112
IMAGE=${ACCOUNT}/seleniumbase:${TAG}

all: build

build:
	cd ../SeleniumBase && docker build -t ${IMAGE} .

push:
	docker push ${IMAGE}
