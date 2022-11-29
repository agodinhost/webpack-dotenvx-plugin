
# Verdaccio setup
npm install -g verdaccio

# Verdaccio, create user
npm adduser --registry {myregistry}

# public npm registry 
registry=https://registry.npmjs.org/

# G&C local network verdaccio server
@gec.js:registry=http://192.168.0.124:4873/

# G&C public verdaccio server
@sandbox:registry=http://189.122.100.39:4873/

# TODO: Accenture gitlab
@accenture:registry=http://accenture.innersource.com

# TODO: Cielo gitlab
@cielo:registry=http://cielo.gitlab.com