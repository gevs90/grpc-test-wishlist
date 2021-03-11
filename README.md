# GRPC with Go
    # Protocol buffers
    ## What is it?
    - IDL interface description language
    - Less error prone
    
    # Command compile proto/wishlist.proto
    $ protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative proto/wishlist.proto