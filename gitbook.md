docker run --rm -v "$PWD:/gitbook" -p 4000:4000 billryan/gitbook gitbook init

docker run --rm -v "$PWD:/gitbook" -p 4000:4000 billryan/gitbook gitbook serve

docker run --rm -v "$PWD:/gitbook" -p 4000:4000 billryan/gitbook gitbook install

docker run --rm -v "$PWD:/gitbook" -p 4000:4000 billryan/gitbook gitbook build