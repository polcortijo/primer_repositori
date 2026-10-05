# Fitxa tècnica: Configuració de xarxa en Linux

## Objectiu

Configurar i comprovar la connexió de xarxa d'un sistema Linux en una màquina virtual.

## Materials

- Màquina virtual amb Linux.
- VirtualBox.
- Connexió de xarxa.
- Terminal de Linux.

## Procediment

1. Iniciar la màquina virtual amb Linux.
2. Obrir el terminal.
3. Consultar la configuració actual de xarxa.
4. Configurar la interfície de xarxa.
5. Comprovar que la màquina té una adreça IP.
6. Comprovar la connectivitat amb una altra màquina.
7. Verificar l'accés a Internet.

Per consultar les interfícies de xarxa es pot utilitzar:

```bash
ip a
```

## Comprovacions

- [ ] La màquina té una adreça IP.
- [ ] La interfície de xarxa està activa.
- [ ] Es pot fer ping a una altra màquina.
- [ ] Es pot accedir a Internet.

## Incidències i solucions

| Incidència | Solució |
|---|---|
| La màquina no té IP | Comprovar la configuració de la interfície de xarxa. |
| No funciona el ping | Comprovar que les dues màquines estan a la mateixa xarxa. |
| No hi ha connexió a Internet | Comprovar l'adaptador de xarxa de la màquina virtual. |

## Recursos

- [Documentació de GitHub](https://docs.github.com/)
- [Documentació d'Ubuntu](https://ubuntu.com/server/docs)

## Foto
(https://openresearch.ed.ac.uk/github/)

## Flux de treball amb Git

El flux de treball bàsic utilitzat en aquesta pràctica és:

1. Modificar els fitxers del repositori.
2. Comprovar els canvis amb `git status`.
3. Revisar els canvis amb `git diff`.
4. Preparar els canvis amb `git add`.
5. Crear un commit amb `git commit`.
6. Consultar l'historial amb `git log`.
7. Enviar els canvis al repositori remot amb `git push`.