![VB6](https://github.com/andresGitDev/InstallVb6InW64Bit/blob/master/images/logo-vb6.jpg)
# Betasepp
## _Instalacion VB6 en Windows 64bit_

Soporte para instalacion de ambiente de trabajo para visual basic 6 sp 6

- ✨Se usaran link de descarga a Mega
- ✨Explicacion paso a paso de instalacion
- ✨Librerias necesarios para funcionamiento

## Features and Tech

- Visual basic 6 sp 6
- Visual Studio View 8.0
- visual Studio Flex Grid 7 Pro
- Active Report
- Librerias OCX y OCA
- Crystal Report
- Afip WebService
- Universal Document
- Office 2003/2007/2010/2014
- Sql Server 2005/2008R2/2014
- Chilkatax 9.5.0

Todo lo explicado en esta guia fue testeado en windows 7/8/10/11, basicamente si solo se desea VB6 en windows 64 bit, solo llegar al paso 1, lo demas es para proyectos de betasepp.

> No salte ningun paso, uno a uno siga las instrucciones

Cualquier error surgido deberia ser solucionado con esta guia, de existir algo nuevo, por favor apuntelo en esta guia.

## 01 - Instalacion de Visual Basic

Utilice los siguientes link

- Primer paso [Visual Basic 6 (Base)](https://mega.nz/file/EiQk1ZAQ#AIew-VCsE87Z3rzMdseyFun9B1XZUbZPwUBcWw224oc)

    -Ejecutar Setup.exe, segun la version de windows puede finalizar
    ![final correcto](https://github.com/andresGitDev/InstallVb6InW64Bit/blob/master/images/install-vb6-final.JPG)

    -O no, quedara como en la siguiente imagen y no termina, cerrar el proceso
        ![final no correcto](https://github.com/andresGitDev/InstallVb6InW64Bit/blob/master/images/install-vb6-no-final.JPG)

- Segundo Pago [Visual Basic (Complemento)](https://mega.nz/file/N2BjlKzJ#xir3Ayg3MXNRFpXMBvBbnWllSWb7Ri-rjnAdk8qPDpA)

    -Sin importar si termina o no la instalacion anterior, ya que termina de registrar librerias
    -Orden de instalacion : vb6.exe, sp6.exe y parcheSp6.msi

## 02 - Instalacion de Visual Studio View

- Descargar [VSView80](https://mega.nz/file/szZRUSZA#KwjIYDvKBi9aYr-I1Rn5VP5J4QreD2EX1zoQxb-VQD4)

    -Ejecutar Setup.Exe y utilizar el numero de serie en Serial.txt

## 03 - Instalacion de Visual Studio Flex Grid

- Descargar [VSFlexGrid7Pro](https://mega.nz/file/M2ZQTKhJ#4xvYmnHZw2IqqBJq-8voCjItgCYq3KwoY1EzCGZww7A)

    -Ejecutar Setup.exe, si falla, colocar las librerias en la carpeta ocx en system32 y syswow64


## 04 - Instalacion de Active Report

- Descargar [ActiveReportEval](https://mega.nz/file/c6pgBIgK#em8PYckVOKWUwL_INcGvdYLoYos6gF0OB9MI58nw7bs)

    -Orden de instalacion: ar2ProEval.exe, ar2ProSp1.exe y ar2ProSp2.exe, luego ejecutar register


## 05 - Instalacion de Librerias para System32 y SysWOW64

- Descargar [X](https://mega.nz/file/EiQk1ZAQ#AIew-VCsE87Z3rzMdseyFun9B1XZUbZPwUBcWw224oc)


## 06 - Instalacion de Crystal Report

- Descargar [x](https://mega.nz/file/EiQk1ZAQ#AIew-VCsE87Z3rzMdseyFun9B1XZUbZPwUBcWw224oc)


## 07 - Instalacion de Afip WebService

- Descargar [x](https://mega.nz/file/EiQk1ZAQ#AIew-VCsE87Z3rzMdseyFun9B1XZUbZPwUBcWw224oc)


## 08 - Instalacion de Universal Document

- Descargar [x](https://mega.nz/file/EiQk1ZAQ#AIew-VCsE87Z3rzMdseyFun9B1XZUbZPwUBcWw224oc)


## 09 - Instalacion de Office 2003/2007/2010/2014

- Descargar [x](https://mega.nz/file/EiQk1ZAQ#AIew-VCsE87Z3rzMdseyFun9B1XZUbZPwUBcWw224oc)


## 10 - Instalacion de SQL Server 2005/2008R2/2014

- Descargar [x](https://mega.nz/file/EiQk1ZAQ#AIew-VCsE87Z3rzMdseyFun9B1XZUbZPwUBcWw224oc)


## 11 - Instalacion de Chilkatax 9.5.0 (Para proceso de QR)

- Descargar [x](https://mega.nz/file/EiQk1ZAQ#AIew-VCsE87Z3rzMdseyFun9B1XZUbZPwUBcWw224oc)

## 12 - Detalles post Instalacion
```sh
error:
Ab2dll.dll is missing
solucion : Paso 05
```

## Plugins

| Plugin | Url |
| ------ | ------ |
| SourceTree | [https://www.sourcetreeapp.com/] |
