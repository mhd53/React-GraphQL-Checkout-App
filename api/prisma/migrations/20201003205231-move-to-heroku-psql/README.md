# Migration `20201003205231-move-to-heroku-psql`

This migration has been generated by mhd53 at 10/3/2020, 4:52:31 PM.
You can check out the [state of the schema](./schema.prisma) after the migration.

## Database Steps

```sql

```

## Changes

```diff
diff --git schema.prisma schema.prisma
migration 20200929203332-create-new-database..20201003205231-move-to-heroku-psql
--- datamodel.dml
+++ datamodel.dml
@@ -2,10 +2,10 @@
   provider = "prisma-client-js"
 }
 datasource db {
-  provider = "sqlite"
-  url = "***"
+  provider = "postgresql"
+  url = "***"
 }
 model Item {
   id         Int @default(autoincrement()) @id
```


