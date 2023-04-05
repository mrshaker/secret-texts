# Secret Texts
It's a secret text platform where you can put your texts as an unknown person.

![Snag_3751ffa](https://user-images.githubusercontent.com/50785245/230067007-532a2d6a-803e-4fb3-8071-6390ecb0f501.png)

![Snag_37584ee](https://user-images.githubusercontent.com/50785245/230067107-27f50516-a62b-4b96-8f32-3592a522194f.png)


# Introduction
First of all register on MongoDB Atlas service and make your cluster, then get your Username and Password and cluster address (more information in MongoDB Doc). Then import them in .env file the following:

USER_NAME=yourUserName

PASSWORD=youPassword

Second, we use google-auth2 for authentication as third-party so, you have to get your Client_id and Client_secret from Google API (use this article https://help.sagecrm.com/on_premise/en/2022R1/Administration/Content/Administrator/EM_GetClientIdSecret-Gmail.htm).
Then import thme in .env file the following:

CLIENT_ID=yourClientId

CLIENT_SECRET=yourClientSecret

CALLBACK_URL=http://localhost:3000 or your special domain.

Then,

```
npm init
npm run start
```

check, localhost:3000

Finally, you can put your secret Texts and see them then survey your data in the MongoDB Atlas cluster.

![Snag_37c2a1a](https://user-images.githubusercontent.com/50785245/230068461-e4a463eb-1ac1-4015-afe8-453e3e3a7fe7.png)

![Snag_37c5c17](https://user-images.githubusercontent.com/50785245/230068498-ac0463e4-1a56-47c3-b93e-20047776fbb9.png)



