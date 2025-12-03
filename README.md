# 🔐 Exemple d’implémentation de la Double Authentification (TOTP)

Ce projet présente un exemple simple et complet de l’intégration de la **double authentification TOTP** dans une application.  
Il permet de sécuriser la connexion des utilisateurs en leur demandant un **code à 6 chiffres** généré par une application d’authentification.

---

## 🧩 Fonctionnalités

- Création d’un compte utilisateur local  
- Activation/désactivation de la double authentification  
- Génération d’un secret TOTP  
- Affichage d’un **QR Code** compatible avec les applications Authenticator  
- Vérification du code à 6 chiffres  
- Connexion sécurisée avec 2FA

---

## 📸 Aperçu de l’interface

### 📝 Création du compte utilisateur
L’utilisateur commence par créer un compte pour pouvoir activer la double authentification.

<img width="448" height="335" alt="Capture d&#39;écran 2025-12-03 164829" src="https://github.com/user-attachments/assets/43e4f55a-02ab-4410-bc57-c9b5bbe7c92c" />

---

### 🔑 Activation de la double authentification (TOTP)
Un QR Code est généré automatiquement.  
L’utilisateur peut le scanner avec :  
- Google Authenticator  
- Microsoft Authenticator

![IMG_3262](https://github.com/user-attachments/assets/8064e337-6706-4313-9989-3e3e8284c7c8)


- ou toute application compatible **TOTP / RFC 6238**

<img width="493" height="526" alt="Capture d&#39;écran 2025-12-03 164910" src="https://github.com/user-attachments/assets/c619f393-99d8-4ed2-9d4d-6cddedcd6cf2" />

---

### 🧾 Saisie du code de vérification
Après avoir scanné le QR Code, l’utilisateur doit entrer son **code TOTP à 6 chiffres** pour se connecter.

<img width="450" height="337" alt="Capture d&#39;écran 2025-12-03 165128" src="https://github.com/user-attachments/assets/5c72fcc2-1645-4c8e-8dbc-66029e2068df" />

---

<img width="503" height="165" alt="Capture d&#39;écran 2025-12-03 165139" src="https://github.com/user-attachments/assets/97a45202-6857-4445-b9c3-e6ad8f0683fb" />


## 🔧 Technologies utilisées

- Génération TOTP (Time-based One-Time Password)  
- QR Code intégré  
- Interface utilisateur simple pour démonstration  
- Compatible avec toutes les apps Authenticator  

---

## 🛠 Comment tester ?

1. Créez un compte utilisateur  
2. Activez la double authentification  
3. Scannez le QR Code avec votre application Authenticator  
4. Déconnectez-vous  
5. Reconnectez-vous  
6. Entrez le code TOTP affiché dans votre mobile  

---

## 🎯 Objectif du projet

Ce projet sert d’exemple pédagogique pour comprendre :
- le fonctionnement d’un **secret partagé**,  
- la génération de codes TOTP,  
- la validation côté application,  
- l’intégration dans un flux de connexion classique.

Idéal pour apprendre ou intégrer dans vos futurs projets logiciels.

---

## 📄 Licence

Libre d’utilisation pour un usage personnel, pédagogique ou démonstratif.
