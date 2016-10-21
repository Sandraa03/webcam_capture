Per poder executar aquest projecte hem de cumplir alguns requisits, com per exemple, tenir el git i el cmake instal·lats. Per comprobar que complim els requisits i executar el projecte haurem de seguir aquests pasos:

1. Assegurar-nos que tenim el git instal·lat per poder clonar el projecte desde github. Per això obrirem una terminal i escriurem ‘sudo apt-get install git’.
A continuació ens demanará la contrasenya de root, en cas que en tinguem. Tot seguit, si ja teniem el git instal·lat ens ho comunicará i podrem passar directament al pas 2, sinò ens demanará confirmació per seguir amb la instal·lació, confirmem i al cap de un moment ja tindrem el git instal·lat.

2. Assegurar-nos que tenim el cmake instal·lat per poder executar el projecte. Per això a la mateixa terminal escriurem ‘sudo apt-get install cmake’.
A continuació ens demanará la contrasenya de root, en cas que en tinguem. Tot seguit, si ja teniem el cmake instal·lat ens ho comunicará i podrem passar directament al pas 3, sinò ens demanará confirmació per seguir amb la instal·lació, confirmem i al cap de un moment ja tindrem el cmake instal·lat.

3. Per executar aquest projecte és necessaria una llibreria de cmake concreta, per instal·larla, en la mateixa terminal, escriurem ‘sudo apt-get install libopencv-dev’.
A continuació ens demanará la contrasenya de root, en cas que en tinguem. Tot seguit, si ja teniem la llibreria instal·lada ens ho comunicará i podrem passar directament al pas 4, sinò ens demanará confirmació per seguir amb la instal·lació, confirmem i al cap de un moment ja tindrem la llibreria instal·lada.

4. A continuació, és necessari copiar el projecte al nostre github, per això accedirem a l’adreça ‘https://github.com/beta-robots/webcam_capture.git’ i buscarem el botó ‘fork’ situat adalt a la dreta. Un cop localitzat, el pulsarem i esperarem uns segons a que copii el projecte al nostre github, per fer aquest pas, és necessari estar loogejat al web github.com.

5. Un cop copiat, haurem de clonar el projecte al nostre PC, per això crearem un directori allà on volguem ubicar el projecte i hi accedirem.
Per crear un directori desde el terminal farem servir la comanda ‘mkdir nom_directori’.
Per accedir a un directori desde el terminal farem servir la comanda ‘cd ruta_directori’.

6. Ara és el moment de clonar el codi del projecte, per fer-ho, desde l’ubicació del directori que hem creat, farem servir la comanda ‘git clone https://github.com/nom_github/webcam_capture.git’

7. Si executem la comanda ‘ls’ podrem observar que en el directori s’ha creat una carpeta anomenada webcam_capture, hi accedim fent servir la comanda ‘cd webcam_capture’.

8. Ara, és necessari crear un nou directori on compilarem el codi, aquest l’anomenarem build. Per fer-ho fem servir la comanda mkdir build’.

9. Ara toca preparar el codi per a poder-lo compilar, per això, farem servir la comanda ‘cmake .’.

10. Un cop preparat el codi, és necessari compilar-lo, per això, farem servir la comanda ‘make’.

11. Ara ja podem executar el programa mitjançant la comanda ‘./webcam_capture’

La proxima vegada que volguem executar el programa, com que ja ho tindrem preparat en el nostre ordinador, només será necessari realitzar el pas 11 desde el directori webcam_capture.

S'ha modificat el programa perque mostri, a partir del píxel central, un rectangle negre de 20x48 píxels.
