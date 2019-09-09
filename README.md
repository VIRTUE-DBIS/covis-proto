# Collaborative Virtual Spaces (covis) - Protobuf Code definition

This Repository defines the services & messages to synchronize different virtual & physical spaces in a VR context.

## Code generation

### Java
Use the normal protobuf java gradle combo. Not done in this repo.

### Csharp
```dotnet build covis-proto.sln```
creates two .cs files in `covis-proto/obj/debug/netstandard1.5/` which include service & message definitions in csharp.