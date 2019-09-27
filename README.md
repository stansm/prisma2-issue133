# prisma2-issue133

To reproduce: 

```
# create mysql db p2_schema_issue
yarn install
yarn prisma2 lift save
yarn prisma2 lift up
``` 

Uncomment `someField` in the `schema.prisma`

```
yarn prisma2 lift save
yarn prisma2 lift up
```
