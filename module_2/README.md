# MD 2.tēma
 _Autors: [Viktors][autors]_
 _Links uz [projektu][projekts]_

# 9.uzdevums:
![2.tēmas 9.uzdevums](../pics/2_9_uzd.png)
# 13.uzdevums:
![2.tēmas 13.uzdevums](../pics/2_13_uzd.png)
- git neredz atšķirību starp orģinālo script.py un nokopētā script.py


# 16.uzdevums:
Komandas ar kurām var iegūt informāciju par veiktajiem commit iepriekšējās nedēļas laikā:
```sh
git log --since=1.weeks
```
```sh
git log --after="1 week ago"
```

# 17.uzdevums:
```sh
git log --author="Laura Pacilio"
```
# 18.uzdevums:
```sh
git log --author="Laura Pacilio" --since="2021-09-01" --before="2021-09-30"
```

# 19.uzdevums:
Laura nav veikusi commit vakar, ievadot git log ar parametriem terminālī netiek izvadīts nekas:
```sh
git log --after="yesterday" --author="Laura Pacilio"
```
# * papildus uzdevums:
Kad tiek veikts commit ir iespēja norādīt parametru --date"cits datums", kas nodrošina commit pievienošanu ar atpakaļejošu datumu.



[autors]: <https://github.com/viqslv>
[projekts]: <https://github.com/viqslv/devops_basic_viktorsr>