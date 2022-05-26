# IziDream TV
## _L'annonceur de live Twitch pour IziDream !_

[![Build Status](https://img.shields.io/static/v1?label=build&message=success&color=brightgreen)](https://github.com/Khaelo/IziDream-TV-BOT) [![Discord](https://badgen.net/badge/icon/discord?icon=discord&label)](https://discord.com/oauth2/authorize?client_id=800157474455552022&scope=bot&permissions=525060271192)

[IziDream TV](https://github.com/Khaelo/IziDream-TV-BOT) est un bot discord pouvant annoncer les streams des joueurs ou de la chaîne Twitch de l'équipe esport [IziDream](https://izidream.gg/).

## Commandes

Liste des commandes avec les explications de celles-ci.

| Commande | Explication | Extension |
| ------ | ------ | ------ |
| !help <command> | Remplacer <command> par une commande pour obtenir de l'aide sur une commande spécifique. | h
| !uptime | Montre le temps de fonctionnement du bot. | timeup, online
| !add Streamer_Name | Ajoute une chaine Twitch à l'annonceur. | +
| !remove Streamer_Name | Supprime une chaine Twitch de l'annonceur. | rem, -, del, delete
| !channel #general ou !channel 979359452291543062 | **Requis!** Canal texte pour les annonces.| ch, chn
| !operator <@187221521297702923> | Choisir un modérateur. | op
| !reaction 👍 | Active une réaction sur le message d'annonce. | react
| !timezone sv-SE Europe/Stockholm | Consultez IANA Subtag registry https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry & IETF RFC 5646 https://tools.ietf.org/html/rfc5646 pour les balises locales et IANA Time Zone Database https://www.iana.org/time-zones & Wikipedia https://en.wikipedia.org/wiki/List_of_tz_database_time_zones pour les fuseaux horaires. | tz
| !message <streamerName> @everyone %name% **%status%**, avec **%game%** : *%title%* | Changement du message d'annonce du stream. Si <streamerName> est rempli, cela changera le message d'annonce de ce streamer. Assurez-vous d'enlever le <>. Prend en charge %name% pour le nom du streamer, %status% pour le type de stream (VOD, LIVE, RERUN), %game% pour le titre du jeu et %title% pour le titre du stream, %link% pour le lien twitch | msg
| !prefix ! | Choisir un modérateur | pfx
| !language english | Change la langue du bot. | lang
| !announcementchannel Streamer_Name #general ou !announcementchannel Streamer_Name 979359452291543062 | Change le canal d'annonce pour le streamer spécifié. | ac
| !streamers | Affiche la liste des streamers ajoutés. | list



## License

[![GitHub license](https://img.shields.io/github/license/Khaelo/IziDream-TV-BOT)](https://github.com/Khaelo/IziDream-TV-BOT/blob/main/LICENSE)