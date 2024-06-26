
# [Built Portfolio With GitHub ](https://github.com/asdomiq/github-portfolio)
- [Sections](#sections-bookmark)
- [Installation](#installation-arrow_down)
- [Pour commencer](#getting-started-dart)
- [Usage](#usage-joystick)
- [Packages utilisés](#packages-used-package)

---

# Sections :bookmark:

- HERO SECTION
- A PROPOS
- EXPERIENCES
- COMPETENCES
- PROJETS
- PARCOURS
- VEILLE
- CONTACT

---

# Installation :arrow_down:

### Vous devez avant tout télécharger ces deux outils afin de pouvoir utiliser le portfolio !

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

#### Soyez sûr que vous possédez les bonnes versions de chaque outil !

```
node --version
git --version
```

## <br />

# Pour commencer :dart:

### Clonez le dépôt !

Pour bifurquer le dépôt, cliquez sur le bouton fork en haut à droite de la page. Une fois le dépôt créé, ouvrez votre terminal et exécutez les commandes suivantes
```
git clone https://github.com/<YOUR GITHUB USERNAME>/developer-portfolio.git

cd developer-portfolio
```

### Installer les packages sur le chemin principal !

```bash
npm install
# or
yarn install
```

Ensuite, lancer le développement :

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) avec votre navigateur pour voir le résultat.

---

# Usage :joystick:

Goto [emailjs.com](https://www.emailjs.com/) and create a new account for the mail sending. In free trial you will get 200 mail per month. After setup `emailjs` account, Please create a new `.env` file from `.env.example` file.

Eg:

```env
NEXT_PUBLIC_EMAILJS_SERVICE_ID =
NEXT_PUBLIC_EMAILJS_TEMPLATE_ID =
NEXT_PUBLIC_EMAILJS_PUBLIC_KEY =
NEXT_PUBLIC_GTM = # For site analytics
NEXT_PUBLIC_APP_URL = "http://127.0.0.1:3000"
NEXT_PUBLIC_RECAPTCHA_SECRET_KEY = # For captcha verification on contact form
NEXT_PUBLIC_RECAPTCHA_SITE_KEY =
```

### Ensuite, Personnalisez les données dans `utils/data` [folder](https://github.com/asdomiq/developer-portfolio/tree/main/utils/data).

Eg:

```javascript
export const personalData = {
  name: "Erwan",
  profile: "/profile.png",
  designation: "Etudiant ; Développeur Web",
  description: "Mon nom est Erwan...",
  email: "erwanmez41@gmail.com",
  phone: "+33 06 .. .. .. ..",
  address: "Bretagne, France",
  github: "https://github.com/asdomiq",
  facebook: "https://www.facebook.com/asdomiq/",
  linkedIn: "https://www.linkedin.com/in/asdomiq/",
  twitter: "https://twitter.com/asdomiq",
  stackOverflow: "https://stackoverflow.com/users/16840768/asdomiq",
  leetcode: "https://leetcode.com/asdomiq/",
  devUsername: "asdomiq",
  resume: "...",
};
```

`devUsername` Used for fetching blog from `dev.to`.

---

---

# Packages Used :package:

| Used Package List  |
| :----------------: |
|        next        |
|  @emailjs/browser  |
|    lottie-react    |
| react-fast-marquee |
|    react-icons     |
|   react-toastify   |
|        sass        |
|    tailwindcss     |

---
