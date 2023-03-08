#Modifcations for XCode projects:

1. remove/rename preprocessor macros JPH_PROFILE_ENABLED and JPH_DEBUG_RENDERER (use them if you have enabled these in your project)
2. remove/rename architectures ARCHS_STANDART and similar and add arm64 or x86_64


#Build

1. select Jolt target scheme
2. Cmd+B to build
3. Change build target (release - debug) and build again
4. If compiling in debug, rename the product file from libJolt.a to libJoltd.a
5. Hopy the lib file to the corresponding platform folder inside JoltPhysics/Lib
