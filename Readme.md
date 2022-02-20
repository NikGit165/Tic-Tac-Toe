# The Tic Tac Toe Project

-----------------------------------------------------------------------------------

## Without JRE

### Build instructions

- Build distributions using maven tool:

```bash
mvn -P without-jre clean package
```

- Use the following archives:
  - `target/tic-tac-toe-${project.version}-windows.zip` for Windows
  - `target/tic-tac-toe-${project.version}-unix.tar.gz` for MacOS or Linux

### Run instructions

- Download [OpenJDK 11](https://jdk.java.net/11/);
- Unzip the downloaded OpenJDK archive;
- Configure the `PATH` environment variable:
  - Add `%JDK_HOME%\bin\` directory for Windows;
  - Add `$JDK_HOME/bin/` directory for MacOS and Linux;
- Re-login or restart computer;
- Unzip the Tic tac toe distribution:
  - Unzip `tic-tac-toe-${project.version}-windows.zip` for Windows;
  - Unzip `tic-tac-toe-${project.version}-unix.tar.gz` for MacOS or Linux;
- Go to unzipped directory;
- Run the game by double-click on the start script:
  - `start.cmd` for Windows;
  - `start.sh` for MacOS or Linux;

-----------------------------------------------------------------------------------

## With JRE

### Build instructions

- Build distributions using maven tool:

```bash
mvn -P with-jre clean package
```

- Use the following archives:
  - `target/tic-tac-toe-${project.version}-windows-with-jre.zip` for Windows
  - `target/tic-tac-toe-${project.version}-macos-with-jre.tar.gz` for MacOS
  - `target/tic-tac-toe-${project.version}-linux-with-jre.tar.gz` for Linux

### Run instructions

- Unzip the Tic tac toe distribution:
  - Unzip `tic-tac-toe-${project.version}-windows-with-jre.zip` for Windows;
  - Unzip `tic-tac-toe-${project.version}-macos-with-jre.tar.gz` for MacOS;
  - Unzip `tic-tac-toe-${project.version}-linux-with-jre.tar.gz` for Linux;
- Go to unzipped directory;
- Run the game by double-click on the start script:
  - `start.cmd` for Windows;
  - `start.sh` for MacOS or Linux;

=====================================================================

## Инструкции по сборке

- Сборка дистрибутивов с помощью инструмента maven:

```bash
 mvn -P без чистого пакета jre
 ```

- Используйте следующие архивы:
- `target/крестики-нолики-${project.version}-windows.zip` для Windows
- `target/tic-tac-toe-${project.version}-unix.tar.gz` для MacOS или Linux

## Инструкции по запуску

- Загрузите OpenJDK 11;
- Разархивируйте загруженный архив OpenJDK;
- Настройте переменную среды PATH:
  - Добавьте каталог %JDK_HOME%\bin\ для Windows;
  - Добавьте каталог $JDK_HOME/bin/ для MacOS и Linux;
- Перелогиньтесь или перезагрузите компьютер;
- Разархивируйте дистрибутив Крестики-нолики:
  - Разархивируйте `крестики-нолики-${project.version}-windows.zip` для Windows;
  - Разархивируйте `крестики-нолики-${project.version}-unix.tar.gz` для MacOS или Linux;
- Перейти в разархивированный каталог;
- Запустите игру двойным кликом по стартовому скрипту:
  - `start.cmd` для Windows;
  - `start.sh`для MacOS или Linux;

---------------------------------------------------------------------------------------------

## С JRE

### Инструкции по сборке

-Сборка дистрибутивов с помощью инструмента maven:

```bash
mvn -P with-jre чистый пакет
```

- Используйте следующие архивы:
  - `target/tic-tac-toe-${project.version}-windows-with-jre.zip` для Windows
  - `target/tic-tac-toe-${project.version}-macos-with-jre.tar.gz` для MacOS
  - `target/tic-tac-toe-${project.version}-linux-with-jre.tar.gz` для Linux
  -

### Инструкции по запуску

- Разархивируйте дистрибутив Крестики-нолики:
  - Разархивируйте `tic-tac-toe-${project.version}-windows-with-jre.zip` для Windows;
  - Разархивируйте `tic-tac-toe-${project.version}-macos-with-jre.tar.gz` для MacOS;
  - Разархивируйте `tic-tac-toe-${project.version}-linux-with-jre.tar.gz` для Linux;
- Перейти в разархивированный каталог;
- Запустите игру двойным кликом по стартовому скрипту:
  - `start.cmd` для Windows;
  - `start.sh` для MacOS или Linux; 