# My experiences for fixing some linux bugs

#### Fixing vscode double repository list

> Download `vscode/aptsources-cleanup.pyz` file and run this command in your bash terminal

```bash
sudo python3 -OEs aptsources-cleanup.pyz
```


#### Enabling apache rewrite mod after installation in linux:

```bash
a2enmod rewrite
```

#### Automating git pull requests

```bash
git config credential.helper store
while true; do git pull; sleep 5; done
```
