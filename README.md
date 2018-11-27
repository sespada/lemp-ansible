## Instalación de Stack LEMP en CENTOS 7 con ANSIBLE

Es prerrequisito tener instalado ANSIBLE

## INSTRUCCIONES:

Correr con SUDO el playbook `lemp'

```bash
 sudo ansible-playbook lemp.yaml -i hosts -v
```

En localhost el puerto 80 nos va a estar esperando con el mensaje de bienvenida de NGINX y en localhost/info.php la tabla de info de PHP
