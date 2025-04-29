# LaKoRuChi - Plataforma d'Aprenentatge de Coreà en Català

LaKoRuChi és una plataforma integral d'aprenentatge de coreà amb interfície en català, dissenyada per proporcionar una experiència immersiva i interactiva.

## Característiques principals

- **Interfície completament en català**: Tota l'aplicació està optimitzada per a catalanoparlants.
- **Exercicis interactius estil Busuu**: Aprèn gramàtica coreana amb exercicis dinàmics.
- **Sistema de vocabulari**: Pràctica i aprenentatge de paraules noves amb repetició espaiada.
- **Integració amb Anki**: Sincronització bidireccional amb Anki per a una millor retenció.
- **IA integrada**: Respon preguntes i proporciona ajuda personalitzada.
- **Sistema de lligues**: Competeix amb altres aprenents per millorar la motivació.
- **Seccions especialitzades**: Hangul, Hanja, converses, contingut audiovisual i més.

## Tecnologies utilitzades

- Frontend: React amb TypeScript
- Backend: Node.js amb Express
- Base de dades: PostgreSQL
- Integració d'APIs: OpenAI, Gemini
- Extensió de navegador: Chrome/Firefox per a extracció de frases
- Add-on d'Anki: Sincronització amb l'aplicació web

## Instal·lació

### Clonació des de GitHub

```bash
# Clonar el repositori
git clone https://github.com/USUARI/LaKoRuChi.git
cd LaKoRuChi

# Instal·lar dependències
npm install
```

### Configuració de variables d'entorn

1. Copia el fitxer `.env.example` a `.env`:
```bash
cp .env.example .env
```

2. Edita el fitxer `.env` amb les teves claus API i configuració de base de dades

### Base de dades

```bash
# Configurar la base de dades PostgreSQL
# Assegura't que PostgreSQL està en execució
npm run db:push
```

### Execució

```bash
# Iniciar l'aplicació en mode desenvolupament
npm run dev
```

### Notes addicionals

- L'aplicació web estarà disponible a `http://localhost:5000`
- Algunes funcionalitats requereixen claus API vàlides (OpenAI, Gemini)
- L'extensió del navegador es troba a la carpeta `extension/`
- L'add-on d'Anki es troba a la carpeta `anki-addon-for-25/`

## Llicència

© 2025 LaKoRuChi - Tots els drets reservats