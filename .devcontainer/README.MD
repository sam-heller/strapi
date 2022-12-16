
# WIP codespaces build
Highlights of why this is rad 
- Instant dev env up and going in under a minute 
- Stable dev and prod docker build artifacserved outt GH

Still WIP, but the first known gocha jere is that

# Github Keeps your Secrets now
Instead of having this passed through env files, any secrets you want to get into your codespaces
```
  JWT_SECRET: ${JWT_SECRET}
  ADMIN_JWT_SECRET: ${ADMIN_JWT_SECRET}
  DATABASE_PASSWORD: ${DATABASE_PASSWORD}

are stored at either the user/project/or org level. (depending on whats what). Screenshots below on how to handle it from your 
```

[](https://user-images.githubusercontent.com/102188982/208077895-fc624ffc-2dc4-4d72-a474-5bc6d937e39d.jpeg)

[](https://user-images.githubusercontent.com/102188982/208077915-85341fd7-ba83-4516-9f0b-cc314b849be3.jpeg)