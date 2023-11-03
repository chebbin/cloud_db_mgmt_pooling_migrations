# cloud_db_mgmt_pooling_migrations
hw 4c

## 1. Connection Pooling Setup


The GCP Instance called hw4c
![Screen Shot 2023-11-02 at 15 48 43](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/3584c7dc-d527-4a2f-b166-48e0550796ec)


Connections screen showing the 0.0.0.0/0 AllowAll network
![Screen Shot 2023-11-02 at 15 49 54](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/65c696b7-3ab6-4a74-8cf6-36bde269bbea)


Microsoft Azure instance called hw4c
![Screen Shot 2023-11-02 at 15 52 28](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/f5f5b30e-b010-4d55-ae63-a0052d6c69d6)


Networking Screen showing AllowAll Firewall name 0.0.0.0
![Screen Shot 2023-11-02 at 15 54 10](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/32c91564-b3a6-4b39-a9f9-fdd77a734d7d)


Screen of Server Parameters showing max connections of 20 and connect timeout of 3
![Screen Shot 2023-11-02 at 15 58 40](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/fda08418-e49b-4a68-b1ef-92ee0c419586)



## 2a. Database Schema and Data:


Azure database schema with two tables (alembic table had already been added, forgot to do a screen shot before)
![Screen Shot 2023-11-02 at 16 07 51](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/64a6678a-f28a-41a4-aa30-5bc42ccef6ee)


GCP database schema only added table 'patients' (despite multiple attempts to add both, I don't know why.
![Screen Shot 2023-11-02 at 16 15 46](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/68d82330-af4b-4c64-af5e-aace3104b0da)


# 2b. Using MySQL Workbench to Generate ERD


Azure Database Schema Structure with two tables (and added alembic version)
![Screen Shot 2023-11-02 at 14 10 09](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/d52229c4-6af8-43e7-ae9b-fcbcfd1fb483)

GCP Database Schema structure with only one table 
![Screen Shot 2023-11-02 at 14 13 53](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/7c57aef5-b961-42d5-b886-706cd1dd48ac)

# 3. SQLAlchemy and Flask Integration
Will do this another time

# 4. Database Migrations with Alembic
![Screen Shot 2023-11-02 at 22 20 02](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/b6eb4fc1-806f-4adb-aef3-555da7db43c8)

I had started doing this activity, and then tried to backtrack by removing the files. I am unable to recover them. This error message mentions the code file that had been deleted which was 112abc4597c and I don't know how to retrieve it. Deleting the files and recloning from github was not able to correct it. 


Also, I had tried opening a file similar to the cpython-29.pyc file that's here and it disabled my google shell and I had to reset it.
![Screen Shot 2023-11-02 at 22 25 41](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/cfa5d0c9-ed01-43bc-acbf-90616bcd21b8)


Cannot push my work to github. I renewed my token recently, could this have something to do with it?
![Screen Shot 2023-11-02 at 22 34 23](https://github.com/chebbin/cloud_db_mgmt_pooling_migrations/assets/141374142/867d19b5-d402-488e-a918-bba7159863a9)
