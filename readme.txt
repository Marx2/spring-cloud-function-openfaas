- compile & publish image to registry:
faas-cli publish -f stack.yml --platforms linux/arm64,linux/amd64

- deploy function:
faas-cli deploy -f stack.yml