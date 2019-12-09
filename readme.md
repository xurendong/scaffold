# Scaffold
Development Environment

### SDK:
Tested under "CentOS 7 x64 1810 GCC 9.1" and "Windows 10 x64 1909 VS 2017 15.8.6".
<br>Uncompress sdk libraries' archives to a folder and the directory structure would look like as following:
- SDK
  - GitHub
    - GCC910
      - BasicX
      - Boost
      - MariaDB
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
<br>Latest version: 2019-12-09
<br>

| library | plateform | version |
| - | - | - |
| BasicX | Linux | V1.0.1 Build 20191209 |
| BasicX | Windows | V1.0.1 Build 20191209 |
| BerkeleyDB | Windows | V18.1.25 |
| Boost | Linux | V1.70.0 |
| Boost | Windows | V1.70.0 |
| Botan | Windows | V2.8.0 |
| CryptoPP | Windows | V7.0.0 |
| Interface | Windows | APE, CTP_F, CTP_F_CT, LTS, TDB, TDF, VIP |
| LevelDB | Windows | V1.2.0 |
| MariaDB | Linux | V3.1.2 (10.4.6) |
| MariaDB | Windows | V3.0.3 (10.2.9) |
| MySQL | Windows | V6.1.11 (5.7.16) |
| OpenSSL | Windows | V1.1.1 |
| SharpX | Windows | V0.1.0-Beta Build 20180906 |
| SQLite | Windows | V3.25.3 |
| SQLiteCpp | Windows | V2.2.0 |
| ZLib | Windows | V1.2.11 |
