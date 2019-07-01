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
      - SQLite
      - SQLiteCpp
      - ZLib

Change the value of "SDKDIR_PATH" in other project's main CMakeLists.txt file to your sdk libraries' folder path.
<br>You'd better recompile these sdk libraries under your development environment.
<br>Latest version: 2019-07-01
<br>

| library | plateform | version |
| - | - | - |
| BasicX | Windows | V0.9.9-Beta Build 20190628 |
| BerkeleyDB | Windows | V18.1.25 |
| Boost | Windows | V1.70.0 |
| Botan | Windows | V2.8.0 |
| CryptoPP | Windows | V7.0.0 |
| Interface | Windows | APE, CTP_F, CTP_F_CT, LTS, TDB, TDF, VIP |
| LevelDB | Windows | V1.2.0 |
| MariaDB | Windows | V3.0.3 (10.2.9) |
| MySQL | Windows | V6.1.11 (5.7.16) |
| OpenSSL | Windows | V1.1.1 |
| SharpX | Windows | V0.1.0-Beta Build 20180906 |
| SQLite | Windows | V3.25.3 |
| SQLiteCpp | Windows | V2.2.0 |
| ZLib | Windows | V1.2.11 |
