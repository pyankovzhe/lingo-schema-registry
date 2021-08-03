## Lingo schema registry

Repository with protobuf schemas for Lingo project.

To generate code run compiler with
```sh
protoc -I=$SRC_DIR --go_out=$DST_DIR $PROTO_DEST
```

Example:
```sh
protoc -I=proto/v1 --go_out=$HOME/go/src/github.com/pyankovzhe/dictionary/pkg/proto ./proto/v1/account-event.proto
```
