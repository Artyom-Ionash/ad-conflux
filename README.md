# Fullstack Authentication Example with Next.js and NextAuth.js

Шаблонное приложение с авторизацией на MongoDB.

```
# После обновления модели требуется выполнить
npx prisma db push

# Примечание: был случай, когда ассоциация по идентификатору в
# MongoDB не работала, и это отрадалось в `npx prisma studio`
# (пользователь не видел свои posts `Post[]`).
# Однако проблема решилась после переприсваивания
№ идентификатора `aduthorId` в `Post`.
```
