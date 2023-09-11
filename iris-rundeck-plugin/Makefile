all: install

clean:
	rm -rf build

build:
	mkdir -p build/libs build/zip-content/iris-rundeck-plugin
	cp -r contents resources plugin.yaml build/zip-content/iris-rundeck-plugin
	cd build/zip-content; zip -r iris-rundeck-plugin.zip *
	mv build/zip-content/iris-rundeck-plugin.zip build/libs

