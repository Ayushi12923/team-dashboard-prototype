Property Dashboard Prototype

This is my prototype project  
I am building a small dashboard to manage properties, tenants, and rent payments.

 Progress so far
Day 1
  - Basic Spring Boot setup done  
  - Added starter Application class  
  - Created placeholder JSP pages (dashboard, properties, rent form, payment list)  
  - Wrote SQL file with only DB creation  

Day 2
  - Added Property entity class  
  - Created properties table in SQL  
  - Updated properties.jsp with “work in progress” note  
  - Hibernate connection still not done  

Day  
  - Added Tenant entity class  
  - Created tenants table in SQL  
  - Added a new JSP page for tenants (currently placeholder)  
  - Updated dashboard page to mention Property + Tenant  
  - Next step: learn how to show DB data on these pages  

Day 4 
  - Added Payment entity class (id, amount, date, tenantName)  
  - Created payment-form.jsp with simple input form  
  - Added payment-list.jsp page (currently placeholder)  
  - Updated SQL with a payments table  

Day 5  
  - Updated dashboard.jsp to show all three entities: Property, Tenant, Payment  
  - Improved JSP placeholders slightly  
  - Application is running fine on `localhost:8080/dashboard`  
  - Still struggling with Hibernate DB connection  

Tech Stack
- Java (Spring Boot)  
- JSP, HTML, CSS  
- MySQL (basic tables only right now)  
- Maven  

How to run (current stage)
1. Open in IDE (I’m using IntelliJ).  
2. Run Application.java.  
3. Go to browser: [http://localhost:8080/dashboard](http://localhost:8080/dashboard).  

At this stage, it only shows placeholder JSPs with “work in progress” messages.  
Database integration is still not working, I plan to try in the next step.  


