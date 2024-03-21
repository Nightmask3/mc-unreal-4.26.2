A fork of the Meshcapade -> Unreal plugin, modified for Unreal 4.26.2.

Had to make some minor changes in the plugin to get it to compile for 4.26.2. Mostly involved adding Eigen as a local library as pre-built 4.26.2 doesn't seem to allow Eigen to be declared as a static dependency (which I see is done in the build.cs file). Also some minor function signature changes from FVector::Length to FVector::Size.
