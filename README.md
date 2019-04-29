# lawapi-nodejs-42
#### Clonez ce depot dans `~/bin`
`git clone https://github.com/malberte/nodejs-42.git ~/bin/nodejs`

#### Faites un lien symbolique de `~/bin/nodejs/bin/` des 3 executables `node`, `npm` et `npx`
`ln -s ~/bin/nodejs/bin/node ~/bin/`

`ln -s ~/bin/nodejs/bin/npm ~/bin/`

`ln -s ~/bin/nodejs/bin/npx ~/bin/`

#### Ajoutez `~/bin` a votre `$PATH` si c'est pas déjà fait dans votre fichier `~/.zshrc` (copiez la ligne ci dessous dedans)
`export PATH=/Users/$USER/bin:$PATH-`

#### Testez la bonne installation
Rechargez le terminal puis

`node --version && npm --version`

Vous obtenez normalement:

`v12.0.0`

`6.9.0`
