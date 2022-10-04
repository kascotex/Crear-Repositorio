•	Create a new repository -> en la cuenta de git (NO Crear README.txt)
•	Copiar dirección      --> ej: https://github.com/pepito/test_01.git
•	crear carpeta       ---> ej: test_01
•	git bash here     ----> dentro de la carpeta creada

•	Instrucciones: create a new repository on the command line

	git init
	crear un README.txt (que contenga una descripcion)
	git add . // git add README.txt
	git commit -m "first commit"
		//si mensaje Author identity unknown:
		git config --global user.email "leomcmlxxiv@gmail.com"
	git branch -M main
	git remote add origin https://github.com/pepito/test_01.git
	git push -u origin main

•	verificar que se creó correctamente (que este el archivo README.txt)

git add .
git status
git commit -m "Commit message"
git push


*******************************************************
 		* * * * para forkear * * * *  
 en al repo ORIGINAL hacer click en fork (ej: https://github.com/pepito/test_01.git)
 crear una carpeta y dentro de ella hacer:
 git clone https://github.com/MiRepo.git (se va a crear la carpeta forkeada)

 dentro de la carpeta forkeada hacer:
 git remote rename origin fork // cambiar "origin" por "fork" para que quede mas claro
 ir al repo ORIGINAL y copiar la direccion (ej: https://github.com/pepito/test_01.git)
 git remote add nomID https://github.com/pepito/test_01.git 
 // nomID = le puedo poner un nombre que lo identifique (ej: pepitoTest)
•	verificar que se forkeo correctamente (editar el archivo README.txt)










