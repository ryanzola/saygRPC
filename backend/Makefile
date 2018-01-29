build: 
	GOOS=linux go build -o app
	docker build -t gcr.io/rz-text-to-speech/say .
	rm -f app

push:
	gcloud docker -- push gcr.io/rz-text-to-speech/say