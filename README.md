# GrpcDemo
This is to demostrate 
1. ProtobufRepo is a separate repo
which can be build to via gradle proto plugin to genreate both client side and server side of code and being packaged into a JAR.
2. The generated Jar then can be used in GrpcClient (containing stub and pojo)
3. The generated Jar then can be used in GrpcServer (which implements the server side )

In the end GrpcClient can call GrpcServer easily via Grpc 
