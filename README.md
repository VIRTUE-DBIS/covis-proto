# Collaborative Virtual Spaces (covis) - Protobuf Definition

This Repository defines the services & messages to synchronize different virtual & physical spaces and objects in a VR context. Use both by the [covis-server](https://github.com/VIRTUE-DBIS/covis-server) and [VREP](https://github.com/VIRTUE-DBIS/virtual-exhibition-presenter)

## Code Generation

### Java
Use the normal protobuf jvm gradle combo. Consider [covis-server](https://github.com/VIRTUE-DBIS/covis-server) as an example. Not done in this repo.

### Csharp
Enter the following command: 
```dotnet build covis-proto.sln```
This creates two .cs files in `covis-proto/obj/debug/netstandard1.5/` which include service & message definitions in csharp which you can then copy to your csharp-project.
