# ElegantNetworking

ElegantNetworking is a packet system framework which seeks to make client-server interaction in MinecraftForge mods as easy as possible. 

For more info look for https://github.com/ElegantNetworking/ElegantNetworkingRoot/blob/master/README.md

## How to setup workspace for contributing
1. Create folder, i.e. `ElegantNetworking`
2. `git clone https://github.com/ElegantNetworking/ElegantNetworkingRoot_java16.git`
3. `git clone https://github.com/ElegantNetworking/ElegantNetworkingCommon.git`
4. `git clone https://github.com/ElegantNetworking/ElegantNetworkingAnnotationProcessor.git`
5. `git clone https://github.com/ElegantNetworking/ElegantNetworking_1.17.git`
6. Import `ElegantNetworkingRoot_java16` gradle project into your IDE
7. `cd ElegantNetworkingRoot_java16`
8. Use `gradlew :ElegantNetworking_1.16:runClient` for run game
9. Use `gradlew :ElegantNetworking_1.16:build` for build runtime library
10. Use `gradlew :ElegantNetworkingAnnotationProcessor:shadowJar` for build annotation processor