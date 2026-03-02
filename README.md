# Resoluci-n-Maquina-Vulnerable1

# Inicio de máquina
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-18 231233" src="https://github.com/user-attachments/assets/d1ebed43-57ad-4332-987c-73c27cb24b3a" />

# Reconocimiento
Una vez iniciamos la maquina vulnerable procedemos hacer un reconocimiento de puertos de la maquina utilizando la herramienta nmap
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 224256" src="https://github.com/user-attachments/assets/733a09a6-760a-4ea3-8026-adf5af9c0cb2" />

Tambien solicitamos a nmap que nos verificara la versión de los servicios que se encuentran ejecutando en los puertos que encontramos abiertos en esta maquina
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 225406" src="https://github.com/user-attachments/assets/8a6ef45a-8712-41df-8b12-5428696aed47" />

Ya teniendo en conocimiento los puertos que tenia abiertos esta maquina procedimos a verificar cada uno de los folder que contenia la pagina en el sitio web
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 224338" src="https://github.com/user-attachments/assets/301891f1-113d-4b71-99a7-09705d1a8494" />

Dentro de ellos encontramos un sitio de login el cual contenia información de como realizar inyección sql
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 224430" src="https://github.com/user-attachments/assets/a825e75d-92c8-44fb-aa6c-713b7d66a401" />

Seguimos verificando en la pagina a ver si encontrabamos algo de mas importancia o que pudiera servirnos
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 224439" src="https://github.com/user-attachments/assets/57b2da80-8619-497d-baa3-761f1fb35d79" />
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 224451" src="https://github.com/user-attachments/assets/126505ad-6cbd-4561-90b4-7e4604389c44" />

y finalmente en una pagina llamada codelab encontramos algunos folder con informacióin sensible, dentro de los cuales encontramos uno llamado passwords.txt asi que procedimos a verificarlo y probar cada uno de los usuarios y contraseñas contenidos en el 
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 224500" src="https://github.com/user-attachments/assets/0d6df10c-0f8e-4dce-87a3-6cd4a26d4f7f" />
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 225228" src="https://github.com/user-attachments/assets/d43bd80a-1f37-4237-ab63-6d4c3103b8e5" />

# Explotación 
Pudimos usar las credenciales encontradas en texto plano e ingresar a la maquina como root
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 231733" src="https://github.com/user-attachments/assets/806c9dc6-fc94-4c66-b2d5-9b09cf1e319c" />
Abrimos el archivo llamado flag.txt
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 231815" src="https://github.com/user-attachments/assets/58c59dfe-c4a8-4fa7-add0-3c68a121737f" />
<img width="1920" height="1140" alt="Captura de pantalla 2026-02-28 231856" src="https://github.com/user-attachments/assets/5b67b32d-234b-4041-bd13-40e06884ce05" />

De esta manera culminamos con esta maquina

