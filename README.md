# atividade

Instalar NodeJs
↳ sudo apt install python3-pip
↳ pip3 install --user nodeenv
↳ source ~/.profile
↳ nodeenv --version
↳ Vá até a pasta em que você quer que o NodeJs fique
nodeenv [nome da pasta em que o NodeJs será instalado]
↳ Para ativar o NodeJs digite source ./[nome da pasta]/bin/activate
O prompt deve indicar que o Node está ativo com o nome da pasta entre parênteses antes do seu usuário
Para testar digite node --version
↳ Para desativar digite deactivate_node
Cuidado, pois ao desativar o NodeJs, o Node-Red também será desativado
3. Instalar Node-Red
↳ Primeiro ative o NodeJs digitando source ./[nome da pasta]/bin/activate
↳ npm install -g node-red
↳ Para ativar o Node-Red digite node-red
↳ Para acessá-lo, copie o endereço de ip que apareceu ao dar o comando anterior, e o cole no navegador
O seguinte link tem um tutorial legalzinho https://archive.is/idE5l
↳ Para sair digite ctrl + C no terminal
Cuidado, pois ao sair o Node-Red será desativado
