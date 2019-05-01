### Add remote
```
conan remote add andrbek "https://api.bintray.com/conan/andrbek/conan"
```

### Include on conaninfo.txt
```
amqpcpp/4.1.4@andrbek/stable
```

### Options:
shared: [True, False], default: shared=False
linux_tcp: [True, False] (only linux), default: linux_tcp=True

### Generators:
cmake