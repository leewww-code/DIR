TAG = 12.6.0-cudnn-devel-ubuntu22.04
REGISTRY = notebook

docker-build:
	docker build -t ${REGISTRY}/base:${TAG} -f Dockerfile .

docker-push:
	docker push ${REGISTRY}/base:${TAG}
