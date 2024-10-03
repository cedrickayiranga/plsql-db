# Assignment1
#### In this file i created a pluggable database and also delete i will demonstrate this processes using pictures

#### We begin with creating a pluggable database it has a PLSQL_CLASS2024DB as its name,it is shown in below picture:






![pluggable db created](https://github.com/user-attachments/assets/e1b84b30-7011-4ae5-be32-6daf8778b8b8)


#### It is succesfully created as shown in the below table:



![table](https://github.com/user-attachments/assets/26ee89fc-328c-4769-92d7-78fd6e97234f)

#### The query below shows that the pluggable database is mounted=not yet ready to use.

![pluggable db created new](https://github.com/user-attachments/assets/7f92d5db-adb0-4aa8-8a5b-2b43982cf4b9)

#### The query below shows that the mounted database can now be used:

![open pdb](https://github.com/user-attachments/assets/1eb519de-1e77-4a26-b3ea-b012796b4001)


#### After the database is ready to be used we created a user with the name KA_PLSQLAUCA:

![user creation](https://github.com/user-attachments/assets/fe856cec-ca72-41be-8b9b-166078ef8a8d)
#### We then proceeded to create a connection using SQL DEVELOPER:
![developer test](https://github.com/user-attachments/assets/ce978452-4db8-4ea3-8ac8-59c8be5c4c95)

#### After creation of a user, connection and PDB.
#### Step 1 is to connect to the database to be deleted.
![step 1 del](https://github.com/user-attachments/assets/4d8b9c6b-5b8f-44fd-8487-3ab4229d90ec)

#### We now proceed with the steps of deleting another created PLUGGABLE DATABASE with the name KA_TO_DELETE_PDB:

![delete pdb created](https://github.com/user-attachments/assets/0de48a24-9a0a-47da-8afe-3ead8b64b816)

#### Now that its created we call the database using alter command in order to be used:

![alter delete pdb](https://github.com/user-attachments/assets/da92c642-4382-40d1-b8a7-608faf7499d9)
### we now close the database before unplugging:

![db closed](https://github.com/user-attachments/assets/d03df900-d3e9-4bfe-a879-d11c14375c76)

#### we unplug the newly created database:
![unplug](https://github.com/user-attachments/assets/7734f9b1-ca48-455c-ac04-2270de0cff0c)

#### After unplugging the pluggable database we now drop the selected database:
![dropped](https://github.com/user-attachments/assets/a20d4a34-cd30-47d2-ac24-bacb0562f5e7)






![user creation](https://github.com/user-attachments/assets/ebc7e130-6d1f-4cee-b044-66e8f395500b)





