<img align="center" src="https://media.licdn.com/dms/image/v2/D4D16AQGUNxQ7NSC05A/profile-displaybackgroundimage-shrink_350_1400/profile-displaybackgroundimage-shrink_350_1400/0/1738695150340?e=1744243200&v=beta&t=oXX-ixT9bR3dJcYCLv4KBs5wjKFoeP0524kFGHQMYmQ" alt="gabriellugo" />

# IMAGE ENCRYPT

<a href="https://github.com/GabrielLugooo/Image-Encrypt/blob/main/README%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/ImageEncrypt%20%20Versión%20Español-000000" alt="Versión Español" /></a>
<a href="https://github.com/GabrielLugooo/Image-Encrypt" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/ImageEncrypt%20Versión%20Inglés-green" alt="Versión Inglés" /></a>

### Objetivos

Image Encrypt Es un CLI que encripta y desencripta imágenes png, jpg, jpeg a una imagen sin sentido y le proporciona la clave para desbloquearla más tarde para que tenga el control total de sus imágenes.

### Habilidades Aprendidas

- Tecnologías Node JS.
- Proteger la información en imágenes mediante técnicas de cifrado y descifrado.
- Capacidad para generar y reconocer firmas y patrones de ataque.
- Mejorar el conocimiento de los protocolos de red y las vulnerabilidades de seguridad.
- Desarrollo de pensamiento crítico y habilidades de resolución de problemas en ciberseguridad.

### Technologías Usadas

![Static Badge](https://img.shields.io/badge/Javascript-000000?logo=javascript&logoSize=auto)
![Static Badge](https://img.shields.io/badge/Jason-000000?logo=json&logoSize=auto)
![Static Badge](https://img.shields.io/badge/Node.JS-000000?logo=nodedotjs&logoSize=auto)

- Javascript
- Jason
- Node.Js

### Vista Previa

<a href="https://ibb.co/C0qF3fJ" target="_blank" rel="noreferrer noopener"><img align="center" src="https://i.ibb.co/5cdVgPY/Screenshot-2021-12-16-at-2-11-16-PM.png" alt="Preview" height="100" ></a>

### Instalación

```sh
npm i -g ImageEncrypt
```

### Modo de Uso

```sh
ImageEncrypt <command> [option]
```

o ejecutarlo directamente usando npx

```sh
npx ImageEncrypt <command> [option]
```

#### Comandos

```sh
help  #prints help info
```

#### Opciones

```sh
  -e, --encrypt              # La imagen to encriptar
  -d, --decrypt              # La imagen to desencriptar
  -c, --clear                # Limpiar la consola predeterminada: false
  --noClear                  # No limpiar la consola predeterminada: true
  -v, --version              # Impresión de la Versión predeterminada de la CLI: false
  -k, --key                  # La clave predeterminada a utilizar para el descifrado: false
  -i, --outputImageFileName  # La imagen de salida
  -p, --outputKeyFileName    # La clave de salida
```

### Ejemplos

#### Comandos

- Para cifrar una imagen myImage.png a encryptedImage.png y guardando la clave a key.txt:

```sh
ImageEncrypt -e myImage.png -i encryptedImageName.png -p keyFile.txt
```

Salida:

```sh
ImageEncrypt v0.0.1
An image encryption node-js cli

✔ Image read successfully
✔ Output image file name is valid
✔ Output key file name is valid
✔ Image data read successfully
✔ Key generated successfully
✔ Image encrypted successfully
✔ Image saved successfully
✔ Key saved successfully

✔ Image encrypted successfully  
Encrypted image: encryptedImageName.png
Key: keyFile.txt
```

- Para descifrar una imagen encryptedImage.png con su llave key.txt a decryptedImage.png:

```sh
ImageEncrypt -d encryptedImage.png -k key.txt -i decryptedImage.png
```

Salida:

```sh
ImageEncrypt  v0.0.1
An image encryption node-js cli

✔ Image read successfully
✔ Key read successfully
✔ Decryption successful
✔ Image saved successfully

✔ Image decrypted successfully
Decrypted Image: decryptedImage.png
```

### Limitaciones

Si bien el cifrado y descifrado es perfecto en las imágenes png, en jpg y jpeg, el funcionamiento no es perfecto. Las imágenes jpg y jpeg tienen pérdidas y, durante el cifrado y descifrado, se modifican algunos valores de píxeles. Sin embargo, la imagen descifrada es muy similar a la imagen original, pero con algunos píxeles modificados.

ImageEncrypt es una copia con fines educativos de <a href="https://github.com/theninza/imcrypt">Imcrypt</a> bajo MIT License.

----

<h3 align="left">Conecta Conmigo</h3>

<p align="left">
<a href="https://www.youtube.com/@gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=55200&format=png" alt="@gabriellugooo" height="40" width="40" /></a>
<a href="http://www.tiktok.com/@gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=118638&format=png" alt="@gabriellugooo" height="40" width="40" /></a>
<a href="https://instagram.com/lugooogabriel" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=32309&format=png" alt="lugooogabriel" height="40" width="40" /></a>
<a href="https://twitter.com/gabriellugo__" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=phOKFKYpe00C&format=png" alt="gabriellugo__" height="40" width="40" /></a>
<a href="https://www.linkedin.com/in/hernando-gabriel-lugo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=8808&format=png" alt="hernando-gabriel-lugo" height="40" width="40" /></a>
<a href="https://github.com/GabrielLugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=80&id=AngkmzgE6d3E&format=png" alt="gabriellugooo" height="34" width="34" /></a>
<a href="mailto:lugohernandogabriel@gmail.com"> <img align="center" src="https://img.icons8.com/?size=50&id=38036&format=png" alt="lugohernandogabriel@gmail.com" height="40" width="40" /></a>
<a href="https://linktr.ee/gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://simpleicons.org/icons/linktree.svg" alt="gabriellugooo" height="40" width="40" /></a>
</p>

<p align="left">
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/Readme%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Versión%20Español-000000" alt="Versión Español" /></a>
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/README.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Versión%20Inglés-Green" alt="Versión Inglés" /></a>

</p>

<a href="https://linktr.ee/gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Créditos-Gabriel%20Lugo-green" alt="Créditos" /></a>
<img align="center" src="https://komarev.com/ghpvc/?username=GabrielLugoo&label=Vistas%20del%20Perfil&color=green&base=2000" alt="GabrielLugooo" />
<a href="" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/License-MIT-green" alt="MIT License" /></a>
