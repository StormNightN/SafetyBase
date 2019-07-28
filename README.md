# Safety Communication (Root project)(Preparing for development)

SafetyCommunication is project, which contains Client and Server applications for safety communication. Projects use OpenSSL library for safety communication and Protobuf for message definition. For logging Spdlog is using.

Project contains three parts:
* **SafetyCommonLibrary** Core of project, will contain API for work with network and ssl, base message definition and other common stuff.

* **SafetyServer** Server for service many clients in multithread mode.

* **SafetyClient** Client part of project.

Project uses the next dependencies:
* **[Openssl](https://github.com/openssl/openssl)** Library for secure communication.
* **[Spdlog](https://github.com/gabime/spdlog)** Library for speed and thread safety logging.
* **[Protocol buffer](https://github.com/protocolbuffers/protobuf)** Data interchange format.