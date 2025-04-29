# Gocroot lite
Gocroot Backend Lite Version, Get starter:
1. Download code from https://github.com/gocroot/lite 
2. Ekstrak and run

```sh
go run .
```
Open your browser with URL http://127.0.0.1:8080


## Setup Server

![image](https://github.com/gocroot/alwaysdata/assets/11188109/3ba8a59a-61a3-4018-9aef-40e35ade12b1)  

Sign Up for a 100MB plan Free for life in [alwaysdata](https://www.alwaysdata.com/en/). Login into your dashboard and follow this instruction:
1. Open the menu Web>Sites>Modify
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/a95bce70-f0fc-4a74-abfa-51ba3dd543d4)
2. In the Configuration section edit command and Environment
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/d88f8fe6-08a3-4efe-9705-3ad5016b80ee)  
   Please set the environment variable in your system:
   ```sh
   MONGOSTRING=YOURMONGOSTRINGACCESS
   ```
   In this menu, you will see an APPID in the title, shown as a number and a home folder used in the github secrets variable.
3. Go to menu REmote Access>SSH>Modify, set a very strong password and tick enable password-based login
4. Set APIKEY in Customer Area>Profile >Managing Tokens>Generate a token
5. Add sshhost, sshusername, sshpassword, sshport, apikey, appid and folder in your GitHub secret>action variable
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/5cc1e831-49d5-47d1-9486-d6f0f748a963)  


## Database

### NoSQL
The first thing to do is prepare a Mongo database using this template:
1. Sign up for mongodb.com and create one instance of Data Services of mongodb.
2. Download [MongoDB Compass](https://www.mongodb.com/try/download/compass), connect with your mongo string URI from mongodb.com
3. Create database name iteung and collection reply  
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/23ccddb7-bf42-42e2-baac-3d69f3a919f8)  
4. Import [this json](https://whatsauth.my.id/webhook/iteung.reply.json) into reply collection.  
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/7a807d96-430f-4421-95fe-1c6a528ba428)  
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/fd785700-7347-4f4b-b3b9-34816fc7bc53)  
   ![image](https://github.com/gocroot/alwaysdata/assets/11188109/ef236b4d-f8f9-42c6-91ff-f6a7d83be4fc)  

### RDBMS
Signup Supabase