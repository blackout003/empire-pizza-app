<div align="center">

# 🍕 Empire Pizza — appli pour ordinateur

**Le jeu de pizzeria [Empire Pizza](https://pizza.egweb.fr), sur Windows, macOS et Linux, avec Discord.**

[**Télécharger la dernière version**](https://github.com/blackout003/empire-pizza-app/releases/latest) · [Jouer dans le navigateur](https://pizza.egweb.fr)

</div>

---

## Pourquoi l'appli ?

C'est le même jeu que sur le site : même compte, même partie, mêmes duels. L'appli ajoute ce que
le navigateur ne sait pas faire, grâce à Discord :

- 🎮 **Statut Discord** : tes amis voient « Joue à Empire Pizza », avec ton stock de pizzas, ta
  production ou ton duel en cours.
- 🔑 **Connexion en un clic** avec ton compte Discord, sans repasser par le navigateur.
- 👥 **Amis Discord** : vois lesquels de tes amis Discord jouent à Empire Pizza, directement dans le
  panneau Amis.
- ⚔️ **Invitations de duel** : défie un ami Discord ; il reçoit une invitation et rejoint ta salle en
  cliquant sur « Rejoindre », même si l'appli était fermée.

Le jeu se met à jour tout seul, comme sur le site. L'appli elle-même se met aussi à jour
(sauf indication contraire ci-dessous).

## Télécharger

Va sur [la dernière version](https://github.com/blackout003/empire-pizza-app/releases/latest) et
prends le fichier qui correspond à ton ordinateur, dans la partie **Assets** :

| Système | Fichier | Mise à jour automatique |
| --- | --- | --- |
| **Windows** 10 / 11 | `Empire-Pizza-…-win-x64.exe` | ✅ |
| **macOS** puce Apple (M1, M2, M3…) | `Empire-Pizza-…-mac-arm64.dmg` | ❌ l'appli te prévient |
| **macOS** Intel | `Empire-Pizza-…-mac-x64.dmg` | ❌ l'appli te prévient |
| **Linux** (toutes distributions) | `Empire-Pizza-…-linux-x86_64.AppImage` | ✅ |
| **Linux** Debian, Ubuntu, Mint… | `Empire-Pizza-…-linux-amd64.deb` | ❌ réinstaller le nouveau `.deb` |

> Ton Mac a-t-il une puce Apple ? Menu  → *À propos de ce Mac* : « Puce Apple M… » = `arm64`,
> « Processeur Intel » = `x64`.

## Installer

L'appli n'est pas signée par Microsoft ni par Apple (c'est payant pour un petit jeu
indépendant). Ton système te demandera donc une confirmation **la première fois seulement**.

### Windows

1. Lance le fichier `.exe`.
2. Si Windows affiche **« Windows a protégé votre ordinateur »** : clique sur
   *Informations complémentaires*, puis *Exécuter quand même*.
3. Suis l'installation ; Empire Pizza apparaît dans le menu Démarrer.

### macOS

1. Ouvre le fichier `.dmg` et glisse **Empire Pizza** dans le dossier **Applications**.
2. Lance l'appli. Si macOS refuse de l'ouvrir : *Réglages Système → Confidentialité et sécurité*,
   descends jusqu'au message sur Empire Pizza et clique sur **Ouvrir quand même**.
3. Quand une nouvelle version sort, l'appli te propose de la télécharger : remplace l'ancienne
   dans *Applications*.

### Linux

**AppImage** (conseillé, se met à jour toute seule) :

```bash
chmod +x Empire-Pizza-*-linux-x86_64.AppImage
./Empire-Pizza-*-linux-x86_64.AppImage
```

Si l'appli ne démarre pas, installe FUSE (`sudo apt install libfuse2` sur Ubuntu / Debian).

**.deb** (Debian, Ubuntu, Mint…) :

```bash
sudo apt install ./Empire-Pizza-*-linux-amd64.deb
```

## Utiliser Discord dans l'appli

1. Ouvre l'**application Discord** sur ton ordinateur (le statut et les invitations passent par elle).
2. Dans Empire Pizza, connecte-toi avec **Discord**, ou lie Discord à ton compte depuis le menu
   du compte. Discord te demande d'autoriser le jeu : accepte.
3. C'est tout : ton statut s'affiche, et le bloc **Amis Discord** apparaît dans le panneau Amis
   et dans le salon de duel.

Sans l'application Discord ouverte, le jeu marche normalement, simplement sans ces fonctions.

## Questions fréquentes

**Ma partie est-elle la même que sur le site ?**
Oui. Connecte-toi avec le même compte (Discord, email ou clé fantôme) : sauvegarde, classement,
amis et duels sont partagés.

**Faut-il une connexion internet ?**
Oui, comme sur le site : le jeu enregistre ta partie sur le serveur. Sans réseau, l'appli affiche
une page « Le four est éteint » avec un bouton pour réessayer.

**Quelles données l'appli garde-t-elle sur mon ordinateur ?**
La taille de la fenêtre et, si tu as connecté Discord, un jeton de connexion Discord **chiffré
par le trousseau de ton système** (il n'est pas écrit sur le disque si ton système n'a pas de
trousseau). Le reste est géré par le site : voir la
[politique de confidentialité](https://pizza.egweb.fr/confidentialite).

**L'appli est-elle sûre ?**
Elle n'ouvre que le site du jeu (et Discord pour la connexion) ; tout autre lien s'ouvre dans ton
navigateur. Elle n'a accès ni à tes fichiers, ni à ta caméra, ni à ton micro. Les fichiers sont
compilés automatiquement par GitHub Actions à partir du code du jeu.

**Discord dit que je joue, mais je n'en ai pas envie.**
Dans Discord : *Paramètres utilisateur → Confidentialité de l'activité*, désactive le partage de
ton activité.

**L'appli s'est fermée toute seule.**
Relance-la : si le problème venait de Discord, elle redémarre sans les fonctions Discord pour ce
lancement, puis réessaie au suivant. Si ça continue, écris-nous (ci-dessous).

**Comment désinstaller ?**
Windows : *Paramètres → Applications*. macOS : glisse Empire Pizza d'*Applications* à la
corbeille. Linux : supprime l'AppImage, ou `sudo apt remove empire-pizza`.

## Signaler un problème

- En jeu : bouton **Support**.
- Par email : [contact@egweb.fr](mailto:contact@egweb.fr) — indique ton système (Windows, macOS,
  Linux) et la version de l'appli (nom du fichier téléchargé).

---

<div align="center">

Ce dépôt ne contient que les fichiers d'installation de l'appli. Le jeu se joue sur
[pizza.egweb.fr](https://pizza.egweb.fr) · [Mentions légales](https://pizza.egweb.fr/mentions-legales)

</div>
