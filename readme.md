"exec": "cd src && go test ./... -v -coverpkg=./... -coverprofile ../coverage/coverage.out && go tool cover -func ../coverage/coverage.out || exit 1"
