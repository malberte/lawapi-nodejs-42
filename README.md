# lawapi-nodejs-42
#### Clonez ce depot dans `~/bin`
`git clone https://github.com/malberte/lawapi-nodejs-42.git ~/bin/nodejs`

#### Faites un lien symbolique de `~/bin/nodejs/bin/` des 3 executables `node`, `npm` et `npx`
`cd ~/bin/nodejs/bin/`
`ln -s node npm npx ~/bin/`

#### Ajoutez `~/bin` a votre `$PATH` si c'est pas déjà fait dans votre fichier `~/.zshrc`
`export PATH=/Users/malberte/bin:$PATH-`

#### Testez la bonne installation

`node --version && npm --version`

Vous obtenez normalement:

`v12.0.0`

`6.9.0`
