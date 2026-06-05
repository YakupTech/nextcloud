# Selfhosted Nextcloud NAS Server

Deze repository bevat documentatie voor mijn selfhosted Nextcloud-omgeving die draait op mijn eigen NAS-server.  
Het doel van deze omgeving is om bestanden, documenten en media veilig zelf te beheren zonder afhankelijk te zijn van commerciële cloudopslagdiensten.

## Inhoud

- [Over het project](#over-het-project)
- [Doel van de omgeving](#doel-van-de-omgeving)
- [Gebruikte technologieën](#gebruikte-technologieën)
- [Netwerkoverzicht](#netwerkoverzicht)
- [Installatie-overzicht](#installatie-overzicht)
- [Beveiligingsmaatregelen](#beveiligingsmaatregelen)
- [Back-upstrategie](#back-upstrategie)
- [Onderhoud](#onderhoud)
- [Toekomstige verbeteringen](#toekomstige-verbeteringen)

## Over het project

Nextcloud is een open-source platform waarmee bestanden, agenda’s, contacten en andere data zelf gehost kunnen worden.  
In deze omgeving draait Nextcloud op een NAS-server binnen mijn thuisnetwerk.

Met deze setup kan ik mijn eigen cloudopslag beheren, bestanden synchroniseren tussen apparaten en mijn data lokaal opslaan.

## Doel van de omgeving

Het doel van dit project is:

- Zelf bestanden hosten op eigen hardware
- Meer controle krijgen over persoonlijke data
- Leren werken met selfhosting, Docker en netwerkbeheer
- Een veilige privécloud opzetten
- Bestanden kunnen synchroniseren tussen laptop, telefoon en andere apparaten
- Basiskennis opdoen van reverse proxy, SSL-certificaten en back-ups

## Gebruikte technologieën

De omgeving maakt gebruik van de volgende onderdelen:

| Onderdeel | Beschrijving |
|---|---|
| NAS-server | Hardware waarop de omgeving draait |
| Nextcloud | Selfhosted cloudopslagplatform |
| Docker | Containerplatform voor het draaien van services |
| Docker Compose | Beheer van meerdere containers |
| MariaDB/PostgreSQL | Database voor Nextcloud |
| Redis | Caching en performanceverbetering |
| Nginx Proxy Manager / Traefik / Caddy | Reverse proxy |
| Let's Encrypt | Gratis SSL-certificaten |
| DDNS | Dynamische DNS voor externe toegang |
| RAID / opslagpool | Redundantie en opslagbeheer |
