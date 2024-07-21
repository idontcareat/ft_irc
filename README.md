# ft_irc

## Avant-propos

Ce projet a été réaliser avec [Théo Zeribi](https://github.com/TheoZerbibi), entre autre le bot est sa réalisation personnelle

**!** Ce serveur a été implementer avec l'utilisation du client *irssi* pour les tests. Les résultats peuvent différé si vous utilisez un autre client.


## Description
ft_irc est un projet de l'école 42 visant à implémenter un serveur IRC (Internet Relay Chat) conforme au RFC 2812. Ce projet permet de comprendre et de maîtriser les concepts de réseau, de gestion de connexions multiples, et de protocoles de communication.


## Fonctionnalités
- Support de multiples clients simultanément
- Gestion des canaux de discussion (création, jointure, départ)
- Implémentation des commandes de base IRC (NICK, JOIN, PART, PRIVMSG, etc.)
- Système de permissions pour les opérateurs de canal
- Messages privés entre utilisateurs
- Gestion des erreurs et des messages de réponse conformes au RFC

## Technologies Utilisées
- Langage : C++
- Bibliothèque réseau : Sockets POSIX
- OS : Linux
- Compilation : Makefile

## Installation et Exécution

### Prérequis
- Avoir `gcc` et `make` installés
- Une connexion internet pour tester avec des clients IRC

### Instructions
Executez le serveur IRC:
```bash
./ircserv [port] [password]
```
## Ressources Externe

- [Network programming guide](https://beej.us/guide/bgnet/pdf/bgnet_a4_c_1.pdf)

- [Irc : Protocol explanation](http://chi.cs.uchicago.edu/chirc/irc.html)

- [ModernIrc : Complete command reference](https://modern.ircdocs.horse/)

- [IRC2812](https://www.tech-invite.com/y25/tinv-ietf-rfc-2812.html) 

- [Irssi Doc](https://irssi.org/New-users/)
