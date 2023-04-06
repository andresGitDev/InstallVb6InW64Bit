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
- Crystal Reports Professional Edition 9.2
- Afip WebService 92.2
- Universal Document 6.5
- Office 2003/2007/2010/2014
- Sql Server 2000/2005/2008R2/2014
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

- Segundo paso [Visual Basic (Complemento)](https://mega.nz/file/N2BjlKzJ#xir3Ayg3MXNRFpXMBvBbnWllSWb7Ri-rjnAdk8qPDpA)

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

- Descargar [Librerias](https://mega.nz/file/c7xC0YpD#vzorXkz0Acg74bmOrYh4a2NFhSlb3wjaMV19aXyHa9w)

    -Copias todas en carpeta C:\Windows\System32 y C:\Windows\SysWOW64
    -Luego dependiendo del proyecto y el error sera necesario cagarlo como componente


## 06 - Instalacion de Crystal Report

- Descargar [CrystalReport9.2](https://mega.nz/file/07QVWQQb#1tn_Rhxoms66WPEvVzi5k5U92g_beasYn2QkRItvyhM)

    -Colgar imagen de disco ISO CrystalReport.iso, ejecutar Setup.exe y utilizar las claves en serial.txt


## 07 - Instalacion de Afip WebService

- Descargar [WsAfipFe92](https://mega.nz/file/syI0hb7J#tT5dwB2egq2ZnHf1x6ljyMKANSlUfEhNFhpvOZEOo6c)


## 08 - Instalacion de Universal Document

- Descargar [UDC65](https://mega.nz/file/Z2hiyKQI#wwEHBAcSoIhdBlZHAahjiZOOvr8ZjdFDPdzVgKGhd1A)

    -Desactivar Antivirus
    -Ejecutar Keygen6.exe, copiar serial , ejecutar Setup.exe y utilizar el serial copiada


## 09 - Instalacion de Off. 2003/2007/2010/2014

- Descargar [Disco 2003](https://mega.nz/file/c3YGRSQa#y4U7UKhQPTJSRsmE4S1plpq_2PmehRl3_KMyRWMfZPA)

    -Clave: Dentro del disco, en la raiz archivo serials.txt

- Descargar [Disco 2007](https://mega.nz/file/07x1XRja#bqAisilVM6qPErS5_SDAwnjFck2CXhJAyxGWEhvJx2M)

    -Clave: Dentro del disco, en la raiz archivo serial.txt

- Descargar [Disco 2010](https://mega.nz/file/Qjgl0YDT#Bll2J5iSSjsTgad-SO2haaGigsr1O00o1cD8_2qvKQs)

    -Clave: Dentro del disco, en la raiz ejecutar Office 2010 Toolkit 2.1.4.exe

- Descargar [Disco 2014](https://mega.nz/file/hm4RgRJB#a3zCHCj7GvJjQ-wys-8LjQygfJftXYdRwsAiBrWFkv0)

    -Clave: Dentro del disco, en la raiz, carpeta activador, seguir instrucciones en imagen instrucciones.jpg

- Segun requiera el proyecto se debe instalar el disco correspondiente para que registre las ocx

## 10 - Instalacion de SQL Server 2000/2005/2008R2/2014

- Descargar [ISO SQL2000 e](https://mega.nz/file/pywiUDpI#GxWJwmVl02VbJaA1DuT7zz_9deJFQ--Q0E6alH6znBU)
- Descargar [ISO SQL2005 A](https://mega.nz/file/13QUXQKD#FPEZTGCj3pQWOsw0RyeG9xlj_CIRvzFpmCdZtHz-k30)
- Descargar [ISO SQL2005 B](https://mega.nz/file/4uI1ES5L#uDgZxQ07LLoRSBxTQgJof5HSuf0iMLPF87-qRPEl4oA)
- Descargar [ISO SQL2008 R2](https://mega.nz/file/F2BiSASC#u7KHCdJtOQfxQX2iUPUZYlBhdVZUr1C8Czkt3NxCCe4)
- Descargar [ISO SQL2014](https://mega.nz/file/JuRl2TCZ#X8MyPK8HrTEq2GIniJ2EpNevUB299c5hbQohtSyhRpc)
- Descargar [TXT Clave for 2014](https://mega.nz/file/o2ZG2SrD#1x1soWnQ_9duh205apTNppDWwaB6Z-NlFgEvOCS67go)
- Descargar [NET 3.5 for 2014](https://mega.nz/file/4yhFFaIb#hnXJhDCHZOJ36BFxz-NbtjsCQyTb5290ac5Ms1CM8Vw)

## 11 - Instalacion de Chilkatax 9.5.0 (Para proceso de QR)

- Descargar [Chilkatax Win32](https://mega.nz/file/53QVHQiY#NK_2bgsP69xs2sXAOD6H3gCoOdouyfrs-NaQouZfr3I)

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
| TeamViewer | [https://www.teamviewer.com] |
| Otros SP | [https://mega.nz/folder/kqgRRQyb#2AhuETnwk4NVHubZH7qZuw] |
