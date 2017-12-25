  /\_/\  __   _   _ _    _       _       _ 
 ((.).))/ /  / \ | | |_ (_)_ __ | |_____| |_ ___ 
  | |||/ /  / _ \| | ' \| | '  \| / / _ \  _/ -_)
 (_/__\)/  /_/ \_\_|_||_|_|_|_|_|_\_\___/\__\___|

## Различные приблуды для души и для дела

### Все ролики, представленные на нем, пренадлежат мне

__Лицензия:__ _MIT_

* Python `2.7`
* `git` должен быть установлен

### Базовая установка Python

Скачайте и установите Python `2.7` 32-бит;
Скачайте и установите Git;

#### 

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/doctormo/GimpPs/master/tools/install.sh)"
```

### Windows установка дополнений для Python `2.7`:

#### via powershell:

	cd $Env:UserProfile
	mv .gimp-2.8 .gimp-2.8.backup
	git clone --depth=1 https://github.com/doctormo/GimpPs.git .gimp-2.8

#### via cmd:

	cd %USERPROFILE%
	ren .gimp-2.8 .gimp-2.8.backup
	git clone --depth=1 https://github.com/doctormo/GimpPs.git .gimp-2.8
