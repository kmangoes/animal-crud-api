## Animal CRUD API  

CSC-340 assignment. Creating CRUD API that will function as the backend for previously created animal gallery frontend.  

---

### Installation  




     

---

### API Endpoints  

Base URL: http://localhost:8080/animals
#### 1. /animals **(GET)**
Gets a list of all animals in the database.  
**Response: JSON array of all animal objects**

#### 2. /{animalId} **(GET)**  
Gets an animal by its unique, numeric ID.  
**Parameters:** Path variable, **Long** animalId (REQUIRED)  
**Response: A single JSON animal object**  

#### 3. /{classification} **(GET)**  
Gets a list of animals of a certain classification.  
**Parameters:** Path variable, **String** classification (REQUIRED)  
**Response: JSON array of animals of a certain classification**  

#### 4. /name **(GET)**  
Gets an animal by its name. 
**Parameters:** Request param, **String** name (REQUIRED)  
**Response: A single JSON animal object**  

#### 5. /animals **(POST)**  
Adds a new animal entry.  
**Parameters:** Request (JSON) body, *without* animalId input  
**Response: New JSON entry**  

#### 6. /{animalId} **(PUT)** 
Updates an existing animal entry. 
**Parameters:** Path variable, Request (JSON) body  

#### 7. /{animalId} **(DELETE)**
Deletes an existing animal entry.
**Parameters:** Path variable, **Long** animalId




