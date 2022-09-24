# Vagrant

Installation sous WSL : 
> https://www.vagrantup.com/docs/other/wsl

Documentation annexe
> https://blog.thenets.org/how-to-run-vagrant-on-wsl-2/


Acceder a la page des download https://www.vagrantup.com/downloads et taper les commandes linux pour récupérer le livrable et l'installé
> curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add - \
> sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main" \
> sudo apt-get update && sudo apt-get install vagrant 

Installation du plugin wsl pour vagrnat : 
> vagrant plugin install virtualbox_WSL2


