# ftx-move-contracts

### Build from source (all platforms)

<details><summary><b>Install Dependencies</b></summary>

- **Go 1.13 or 1.14**

  Installation instructions can be found here: https://golang.org/doc/install.
  Ensure Go was installed properly and is a supported version:
  ```sh
  $ go version
  $ go env GOROOT GOPATH
  ```
  NOTE: `GOROOT` and `GOPATH` must not be on the same path. Since Go 1.8 (2016),
  `GOROOT` and `GOPATH` are set automatically, and you do not need to change
  them. However, you still need to add `$GOPATH/bin` to your `PATH` in order to
  run binaries installed by `go get` and `go install` (On Windows, this happens
  automatically).

  Unix example -- add these lines to .profile:

  ```
  PATH="$PATH:/usr/local/go/bin"  # main Go binaries ($GOROOT/bin)
  PATH="$PATH:$HOME/go/bin"       # installed Go projects ($GOPATH/bin)
  ```
  
  - **Git**

  Installation instructions can be found at https://git-scm.com or
  https://gitforwindows.org.
  ```sh
  $ git version
  ```
