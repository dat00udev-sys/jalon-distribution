# Installer Jalon

## Avant de commencer

Il vous faut un téléphone ou une tablette sous **Android 8 ou version suivante**. Aucun compte Jalon ni compte GitHub n'est nécessaire.

Le fichier à installer est **Jalon-1.1.0.apk**, dans les *Assets* de la [Release 1.1.0](https://github.com/dat00udev-sys/jalon-distribution/releases/tag/v1.1.0). Les archives « Source code » ne sont pas l'application.

## Installer

1. Ouvrez la Release dans le navigateur du téléphone et téléchargez **Jalon-1.1.0.apk**.
2. Ouvrez le fichier téléchargé. Si Android le demande, autorisez l'installation depuis ce navigateur ; le nom du réglage varie selon le téléphone.
3. Confirmez l'installation, puis ouvrez **Jalon** et créez votre premier chantier.

Au premier lancement, renseignez votre entreprise dans **Réglages** (nom, adresse, SIRET, assurance, médiateur) : ces informations sont obligatoires sur les devis et les factures.

## Mettre à jour sans perdre vos données

Jalon vérifie lui-même s'il existe une nouvelle version, à chaque ouverture, et affiche un bandeau sur l'accueil. Touchez **« Mettre à jour »** : le fichier se télécharge dans le navigateur, puis Android demande l'accord pour l'installer.

Installez toujours la nouvelle version **par-dessus** l'existante, sans désinstaller : les mises à jour officielles ont la même signature, et vos chantiers, clients, prix et photos sont conservés.

**Vous aviez Chantier Élec, une version d'essai ?** Elle était signée avec une autre clé : Android refuse de l'écraser. Une seule fois :
1. dans Chantier Élec, Réglages › Sécurité et sauvegarde › « Enregistrer une sauvegarde maintenant » ;
2. désinstallez Chantier Élec ;
3. installez Jalon ;
4. dans Jalon, Réglages › Sécurité et sauvegarde › « Restaurer une sauvegarde », et choisissez le fichier.

Pensez à faire une sauvegarde de temps en temps (Réglages › Sécurité et sauvegarde), ou à activer la sauvegarde automatique dans un dossier comme Google Drive.

## Vérifier le fichier

Le fichier `SHA256SUMS.txt` contient l'empreinte de chaque APK. Pour la contrôler sous Windows (PowerShell) :

```powershell
Get-FileHash .\Jalon-1.1.0.apk -Algorithm SHA256
```
