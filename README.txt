Iris build steps:

build image - `qmk compile -kb keebio/iris/rev2 -km dvorak_iris`
flash image - `qmk flash -kb keebio/iris/rev2 -km dvorak_iris`

Ergodox Infinity:

build image - `qmk compile -kb input_club/ergodox_infinity -km dvorak_ergo`
flash image - `qmk flash -kb input_club/ergodox_infinity -km dvorak_ergo`

To flash the keyboard using QMK's Docker container:

cd /Git/qmk_firmware
sudo ./util/docker_cmd.sh make input_club/ergodox_infinity:dvorak_ergo
