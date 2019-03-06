Instructions to deploy SNAP Analysis Web App:

1. Login to PCF instance
2. Create `snap-mysql-db service`, ie:
```
cf create-service p-mysql 100mb snap-mysql-db
```
3. Push SNAP app: (app metadata contained in manifest file)
```
cf push
```
> The username is user and password is bekind
