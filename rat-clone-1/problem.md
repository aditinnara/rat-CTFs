# Guess My Cheese

- Namespace: picoctf/18739
- ID: rat-clone-1
- Type: custom
- Category: Cryptography
- Points: 1
- Templatable: yes


## Description

Try to decrypt the secret cheese password to prove you're not the imposter!

## Details

Connect to the program on our server: `nc {{server}} {{port}}`
Download the program: {{url_for("challenge.py")}}

## Challenge Options

```yaml
cpus: 0.5
memory: 128m
pidslimit: 20
ulimits:
  - nofile=128:128
diskquota: 64m
init: true
```
