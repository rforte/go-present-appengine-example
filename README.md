from root directory of repo:

GOPATH=$PWD goapp get golang.org/x/tools/cmd/present
> # golang.org/x/tools/cmd/present
> runtime.main_main: main.main: not defined
> runtime.main_main: undefined: main.main
cp -R src/golang.org/x/tools/cmd/present app/present
GOPATH=$PWD goapp serve app/app.yaml
