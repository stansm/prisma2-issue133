# prisma2-issue133

To reproduce: 


```
yarn prisma2 lift save
yarn prisma2 lift up
``` 

Uncomment someField in the `schema.prisma`

```
yarn prisma2 lift save
yarn prisma2 lift up
```