## Getting Started

First download the dependencies with
```bash
npm i
# or
yarn install
# or
pnpm install
```
then create a .env with 
```
BETTER_AUTH_SECRET=Your secret
BETTER_AUTH_URL=Your URL 

BASE_URL=Your Base

DATABASE_URL=mysql://user:password@localhost:3306/databasename

```

then create your mysql database (or change database configuration in .env and schema)

finally, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
 ## Enjoy
