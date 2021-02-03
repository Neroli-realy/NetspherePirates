# NetspherePirates [![Build status](https://gitlab.com/NetspherePirates/netspherepirates/badges/dev/pipeline.svg)](https://gitlab.com/NetspherePirates/netspherepirates/pipelines)
Experimental S4 League server emulator for patch 34(EU v1139 - Season 1).

### Requirements
* [.Net Core 2.1](https://www.microsoft.com/net/download/dotnet-core/2.1)
* [MariaDB](https://mariadb.org/) or [MySQL](https://www.mysql.com/)
* [Redis](https://redis.io/)
* **Windows only:** [.Net Framework 4.7.2](https://www.microsoft.com/net/download/thank-you/net472)
* S4 League Client - Patch 34(EU v1139): [Download(mega.nz - 450 MB)](https://mega.nz/#!yYMGFYiZ!NTbARFyS8EVjItp1nNTZD9-0WJDO2uK_08ajWoTaUwo)

Docker images are available [here](https://hub.docker.com/u/netspherepirates).


# Usage 

1. Download the Compiled [Binaries](https://github.com/Neroli-realy/NetspherePirates/blob/dev/binaries.rar)

2. copy `DataExtractor.exe` into your `FumbiClient` folder then run it which will export `data` folder

3. copy `data` folder into new folder and place the `Auth` and `Game` folders beside it 
![image](https://user-images.githubusercontent.com/25514920/106760093-19b07e00-663c-11eb-95e2-fb833fca64ee.png)

4. edit `config.hjson` with your database username and password in `Game` and `Auth` folders

5. if you will run it on windows download [redis](https://github.com/ServiceStack/redis-windows/blob/master/downloads/redis-latest.zip) from here

6. run `redis-server` 

7. run `Auth\start.bat`

8. run `Game\start.bat`



