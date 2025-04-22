
# Laboratory 1 

## Name: Miguel Angel Suarez Cortes

## Diagram

![Diagram of micro services](https://i.imgur.com/q5io87q.png)


## System Properties
-   **Modularity**   **Quality property**
    
    -   **Description:** The system is organized into folders and layers (models, repositories, services, controllers, templates), which isolates responsibilities and eases maintenance.
        
    -   
        
-   **Deployability**   **Quality property** (internal).
    
    -   **Description:** The use of Docker and Docker Compose ensures the system can be built and brought up identically in any environment.
        
    -  
        
-   **Maintainability** **Quality property**
    
    -   **Description:** Thanks to the layered pattern and Flask blueprints, each module is decoupled, simplifying updates, bug fixes, and testing.
        
    -   
        
-   **Testability** **Quality property**
    
    -   **Description:** The lab includes clear steps for manually verifying business logic and database state, reflecting a design oriented toward verification.
        
    -  
        
-   **Scalability** **Externally visible** (noticeable in performance and capacity as load grows).
    
    -   **Description:** Although it’s a monolithic architecture, separating the database from the application allows vertical scaling (adding more resources) and even migrating toward microservices in the future.
