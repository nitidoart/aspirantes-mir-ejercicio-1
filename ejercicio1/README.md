1. Me ubique en el directorio
unriccio 🦔  ~ $cd Desktop 

2. Cree carpeta ejercicios
unriccio 🦔  Desktop $ mkdir ejercicios

3. Me ubique enb la carpeta
unriccio 🦔  Desktop $ cd ejercicios 

4. abri la carpeta desde la terminal a VS
unriccio 🦔  ejercicios $ code .

5. En VSCode crear una carpeta ejercicio1.

6. Cree archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.

7. En la terminal me ubique en la carpeta ejercicio1
unriccio 🦔  ejercicios $ cd ejercicio1 

8. Verifique contenido de carpeta
unriccio 🦔  ejercicio1 $ ls
README.md


9. Verifique configuarcion de correo desde la terminal
unriccio 🦔  ejercicio1 $ git config --list


10. Posicionado en la carpeta ejercicos inicialice repositorio
unriccio 🦔  ejercicios $ git init

11. Verifique que el archivo estuviera creado
unriccio 🦔  ejercicios $ ls -a

12. Verificamos que cambios hay
unriccio 🦔  ejercicios $ git status

13. unriccio 🦔  ejercicios $ git add .

14. unriccio 🦔  ejercicios $ git status

15. unriccio 🦔  ejercicios $ git commit -m"Version Inicial"
[master (root-commit) 5b136df] Version Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/README.md

16. Verificar el commit
unriccio 🦔  ejercicios $ git log
commit 5b136df7c231a69610aa163334849974e7f04e2b (HEAD -> master)
Author: Ricardo López <josericardolopezsierra@gmail.com>
Date:   Thu Mar 2 00:57:48 2023 +0100