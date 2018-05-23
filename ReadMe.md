# Hướng dẫn tự build một Docker image Caddy trên Alpine
# Nghịch thử

# Viết script để tự động hoá docker build, docker run
Các file script rebuild, website, hostmd được viết để chạy bằng [fish shell](https://fishshell.com/). Bạn có thể chạy bằng bash shell bằng cách
thay đổi dòng đầu shebang từ #!/usr/local/bin/fish sang #!/bin/bash

**Build docker image sau đó, truy cập đến http://localhost**
```
$ ./rebuild
```

**Host một web site tĩnh**
```
$ ./website
```

**Host một web site chứa markdown (thư mục md) sử dụng Caddy markdown plugin**
```
$ ./hostmd
```
