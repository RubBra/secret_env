# senf
A bash script to securely save and retreive secret environment variables.

## getting started

The first time you run the -add command you can input your password
```bash
./senf -add
```

It is recommended to move the senf script to your home so you can call
```bash
source ~/senf
```
from anywhere

## usage

secret env variables to your env:
```bash
source ./senf
```

Adding env variable definitions:
```bash
./senf -add
```

Removing env variable definitions:
```bash
./senf -remove <var name>
```

Printing all saved definitions:
```bash
./senf -print
```

## good to know

your encripted environment variables and a password salt will be saved in ~/.config/senf
