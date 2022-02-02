TO USE OPENFOAM WE NEED TO UNDERSTAND HOW TO USE EDITOR VI

Here are few commands which are most popularly used in openfoam

To download openfoam in your personal computer , download openfoam from official website www.openfoam.com

EDITOR VI IS USED IN LINUX OR UBUTU TO EDIT THE FILES 

vi <name of file>      ----------- it will open the file
  
:q                      -----------quite the editor
  
wq                      ------------write and quite from editor
  
insert                  ------------to edit the file
  
escp                    -------------to stop writing in the editor, it will stop from editing in th file
  
:q!                     --------------exit without modifing

  
HOW TO OPEDRATE AZUR CLOUD
please  follow the following steps
  
eval $(ssh-agent)                   ----------------- it will create key to access the cloud
  
ssh-add ~/.ssh/<name of pem file>   ------------------ it will let you enter into azur cloud, pem file is created when we create a virtual machine in azur cloud
  
tar xvf <.tar file name. >         ------------------- it will unzip all the tar files

scp -r rhoSimpleFoam.tar.bz2 azuuser@51.103.32.219:/home/azuuser ----------------to transfer data from local pc to azur cloud server machine
  
scp -r files1.tar.bz2 azuuser@51.103.37.27:/home/azuuser/insulatio---------------- same as above


