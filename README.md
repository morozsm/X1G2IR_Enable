# Lenovo X1 Extreme Gen2 IR emitter enable for howdy on Fedora 31
This trivial playbook was designed to automate IR emitter camera fix
on Lenovo X1 Extreme Gen2 laptop.
Playbook installs [@PetePriority's tool for enableing IR emitter](https://github.com/PetePriority/chicony-ir-toggle)
Playbook designed to work on Fedora 31 with 

`04f2:b67c Chicony Electronics Co., Ltd Integrated Camera`

however udev rule can be modified for other OS and cameras.

## Usage
sudo ansible-playbook enable_ir.yml

## Links
[Howdy project](https://github.com/boltgolt/howdy)

[@PetePriority's tool for enableing IR emitter](https://github.com/PetePriority/chicony-ir-toggle)
