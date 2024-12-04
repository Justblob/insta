Prikazy:
Is-yypise obsah domovskeho priecinka
cd-change directory (napr.- cd Dokumenty/dev)
npx create-next-app@latest - prikaz na instalaciu o
npm run dev – spustenie
npm run build – alt spustenie (skompiluje cely projekt ako celok)
npm install @mui/material @emotion/react @emotion/styled - prikaz na instalaciu mui
ak nejde instalacia mui ( 1 error) tak : -npm audit fix –force
konfiguracia githubu
git init - 
git branch -m main-
git config --global user.name "dominator00700"
git config --global user.email "dominatordlk@gmail.com
git remote add origin https://github.com/dominator00700/insta.git
git remote -v
git add .
npm run build


Poznámky:
1. hodina
GRID - The Grid component works well for a layout with a known number of columns. The columns can be configured with multiple breakpoints to specify the column span of each child.
COTAINER - While containers can be nested, most layouts do not require a nested container.
BOX - The Box component is a generic, theme-aware container with access to CSS utilities from MUI System.
2. hodina
github je nasa kolekcia suborov s kotrymi pracujeme, ktoré nakoniec kompilujeme a oridávame do živého internetu pomocou stránky Vercel. Na github ukladáme pomocou „commit“ a „sync changes“ toto nám umožní preniesť lokálne zmenu kódu priamo na iternet

Prihlásenia:
GitHub - dominatordlk@gmail.com	tUpec_king007
Vercel – dominatordlk@gmail.com +421 910 307 666 (insta-xi-eight.vercel.app)


3. hodina

#1. Vercel -> Storage:
    Neon -> Create -> Accept -> Region -> Frankfurt, Germany-(fra1) -> Connect
    in snap-zoska-4h-postgres:
    .env.local -> Show secret -> Copy snippet into your src/.env 

#2. VsCode:
    npm install @prisma/client @auth/prisma-adapter
    npm install prisma --save-dev
    npx prisma init

#3. VsCode:
    In .env replace value of DATABASE_URL
    .env
    package.json:   "build": "prisma generate && next build",
                    "postinstall": "prisma generate"


#4. VsCode terminal:
    npx prisma format
    npx prisma migrate dev --name init
    npx prisma generate
    npx prisma studio
