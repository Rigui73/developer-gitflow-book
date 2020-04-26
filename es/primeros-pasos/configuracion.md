# Configuración

Una vez instalado, debemos configurar el programa GIT, con la información de usuario para un mayor control y buenas practicas.

Iniciaremos la terminal en BASH:

```bash
git config --global user.name "[Nombre] [Apellido]"
```

> Configuramos nuestro nombre y apellido.

```bash
git config --global user.mail [correo]
```

> Configuramos nuestro correo preferiblemente el mismo que en Github/GitLab/etc.

```bash
git config --global color.ui true
```

> Se utiliza para colorear nuestro sistema de comandos y ser mas amigable.

```bash
git config --global core.editor "[RUTA EXECUTABLE] --wait"
```

Podemos configurar la terminal para cuando necesitamos editar texto se nos abra un editor de texto en concreto o dejar el por defecto VIM.

{% hint style="info" %}
Estos parámetros se pueden configurar desde el mismo fichero de configuración de GIT.
{% endhint %}

