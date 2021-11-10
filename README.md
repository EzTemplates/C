# Setup
Create a new repo, either with github or cloning this locally. Set required values in the Makefile (Change TARGET). After that run `make ignore`,
now you can freely change anything under `src/` and `include/`.


## Install the resulting binary
You can use both DESTDIR and PREFIX with this template!
<br>
```sh
$ make PREFIX=/usr/local/bin install
```
