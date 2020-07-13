# Java
Having to sorted arrays, implement a function that will merge the arrays into one sorted array.
```
public static int[] merge(int[] a, int[] b) {

}
```

# SQL
```
--Given the following tables:
CREATE TABLE users
(
    user_id  NUMBER(6) PRIMARY KEY,
    username VARCHAR2(32),
    role_id  NUMBER(6)
);  

 
```
CREATE TABLE roles
(
    role_id   NUMBER(6),
    role_name VARCHAR2(255),
    CONSTRAINT pk_roles PRIMARY KEY (role_id)
);
```
 
```
ALTER TABLE users
    ADD (
        CONSTRAINT fk_users_roles FOREIGN KEY (role_id) REFERENCES roles (role_id)
        );
```
 

-- Questions  
-- 1. Add constraint for minimum username to be 5 characters. (what problems may arise from this change?)  

-- 2. Alter relationship between users and roles table to Many-To-Many. (what extra steps would you take if the tables already contained data?)  
