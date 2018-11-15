# Scaffold
Development Environment

### SDK:
Currently provide Microsoft Visual Studio 2017 support only.
<br>Uncompress sdk libraries' archives to a folder and the directory structure would look like as following:
- SDK
  - GitHub
    - VS2017
      - BasicX
      - BerkeleyDB
      - Boost
      - Botan
      - CryptoPP
      - Interface
      - LevelDB
      - MariaDB
      - MySQL
      - OpenSSL
      - SharpX
      - ZLib

Change the value of "SDKDIR_PATH" in other project's main CMakeLists.txt file to your sdk libraries' folder path.
<br>You'd better recompile these sdk libraries under your development environment.
<br>Latest version: 2018-11-15
<br>

| library | version |
| - | - |
| BasicX | V0.5.5-Beta Build 20180828 |
| BerkeleyDB | V18.1.25 |
| Boost | V1.65.1 |
| Botan | V2.8.0 |
| CryptoPP | V7.0.0 |
| Interface | APE, CTP_F, LTS, TDB, TDF, VIP |
| LevelDB | V1.2.0 |
| MariaDB | V3.0.3 (10.2.9) |
| MySQL | V6.1.11 (5.7.16) |
| OpenSSL | V1.1.1 |
| SharpX | V0.1.0-Beta Build 20180906 |
| ZLib | V1.2.11 |
