# LÉBOU BATI-PLUS — CONTEXTE DE RÉFÉRENCE

## Client
LÉBOU BATI-PLUS — Construction et Immobilier.

## Objectif
Plateforme web immobilière publique, sécurisée et hébergée.

## Géographie
Tout le Sénégal, particulièrement Thiès.

## Besoins validés
- tous les biens immobiliers pertinents
- recherche et filtres avancés
- fiches détaillées
- carte/localisation
- comptes clients
- demandes achat/location
- demandes de visite
- WhatsApp/email
- deux administrateurs
- administration sécurisée
- services et réalisations
- mini-charte graphique
- maintenance

## Activités de l’entreprise
- achat / vente / foncier
- location
- gestion locative
- architecture
- construction / BTP
- réalisations

## Décisions
- 3D et visite virtuelle : V2/V3
- délai cible : 20 jours maximum
- qualité et réussite du projet prioritaires sur un respect artificiel du délai

## Architecture
Next.js + TypeScript + Tailwind + shadcn/ui
-> NestJS + TypeScript
-> Prisma
-> PostgreSQL
-> Cloudflare R2
-> MapLibre + fournisseur de tuiles de production
-> Docker + Nginx + Cloudflare + VPS Linux
-> GitHub Actions

## Données
Property = bien physique
PropertyOffer = offre commerciale
Request = demande liée à une offre

Entités V1 :
User, Session, Property, PropertyType, PropertyOffer, Feature,
PropertyFeature, PropertyMedia, Request, Service, Project,
ProjectMedia, SiteSetting, AuditLog.

## Contraintes
- pas de microservices V1
- pas de paiement en ligne V1
- pas de 3D V1
- pas de messagerie interne V1
- pas d’application mobile V1
