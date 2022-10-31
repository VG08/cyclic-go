# Cyclic go
## run go apis on cyclic
This is an example on running go apis on cyclic. What this does is use the package.json
to run a go binary.
<br>
Ensure the binary is compiled in the following way
<br>
### ``CGO_ENABLED=0 go build``
This might take much longer to compile this way as it will rebuild most of the packages of the stadard library which makes the binary statically linked. Doing so avoid issues with glibc.
