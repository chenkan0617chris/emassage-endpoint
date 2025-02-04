This is the emassage backend API project.

# Express.js + Prisma + PostgreSQL

# Start
```bash
# install package
npm install

# init database
npx prisma init

npx prisma generate

npx prisma migrate dev --name init

# delete all data from database and update schema
npx prisma db push

# run
npm run start

```
