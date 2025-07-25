# HandsMen Threads: Elevating the Art of Sophistication in Men's Fashion  



## ABSTRACT  

The project presents the implementation of a customized Salesforce CRM solution for HandsMen Threads, a premium men's fashion and tailoring brand. The objective was to streamline business operations, enhance customer engagement, and maintain data integrity across departments.
The solution involves designing a robust data model featuring five key custom objects: Customer, Order, Product, Inventory, and Marketing Campaign. Business processes were automatically focused: Triggered Flows, Scheduled Flows, Partial Arms, and Apex to handle other confirmations, highly status updates, and proactive stock alerts.
To ensure clean and reliable data, validation rules were established, and a role-based security model was implemented in the Sales, Inventory, and Marketing teams. The solution also includes a scheduled batch job using Apex to enable new sales quantities.
This end-to-end CRM implementation improves customer experience through personalized communication, ensures operational efficiency with automation, and lays a scalable foundation for future business growth using the Salesforce Platform.


## OBJECTIVE

The main objective of this project is to develop and implement a customized Salesforce CRM validator for Handwake Threads to streamline core business operations, maintain data integrity, and enhance customer satisfaction.
By building a centralized system to manage customers, orders, products, inventory, and marketing campaigns, the project aims to:
•	Automatic key processes such as order confirmations, loyalty status updates, and stock alerts.
•	Ensure accurate and consistent data entry using validation rules.
•	Enable real-time visibility of inventory and customer interactions.
•	Improve internal team coordination through role-based access control.
•	Deliver personalized customer experiences through targeted communication and loyalty programs.


## TECHNOLOGY DESCRIPTION

### Salesforce :
Salesforce is a cloud-based Customer Relationship Management (CRM) platform that helps businesses manage customer data, automate processes, and improve service, marketing, and sales operations. It provides paths and click tools as well as programmatic capabilities (like APIs and Flows) to build custom business solutions.

### Custom Objects :

Objects in Salesforce are like tables in a database. Custom Objects are created to store specific data.

Example:

•	Customer_ c – Stores customer info

•	Product_ c – Stores product details

•	Order_ c – Stores orders<br>


Handsmen Customers object 
<img width="868" height="599" alt="image" src="https://github.com/user-attachments/assets/359b9e4c-36b9-4c5a-8012-74d0fe7dc50a" /><br><br>
Handsmen Products object
 
<img width="868" height="480" alt="image" src="https://github.com/user-attachments/assets/94638d3e-3256-4a1a-be4d-5bfa61e20e33" /><br>

Handsmen Orders object
 
<img width="868" height="611" alt="image" src="https://github.com/user-attachments/assets/b91d08f4-3202-43e9-aa58-c46a28036f67" /><br><br>
Inventorys object

<img width="868" height="537" alt="image" src="https://github.com/user-attachments/assets/d6d46041-acb7-498a-9d9e-2d4525ec15fe" /><br><br>


### Tabs :

Tabs are used to display object data in the Salesforce UI.
Example: A lab for Product_ c allows users to easily view and manage products.
 
<img width="868" height="51" alt="image" src="https://github.com/user-attachments/assets/2716f837-2d8e-4112-a2de-57f7a3c89bd5" /><br><br>

### Custom App :<br>
An App in Salesforce is a collection of tabs grouped together for a specific business purpose.
 <img width="695" height="474" alt="image" src="https://github.com/user-attachments/assets/7af87909-b182-4f28-80eb-9a193dd57490" /><br><br>

### Profiles :<br>
Profiles define what a user can see, do, and edit in Salesforce. It controls object permissions, field access, and more.<br><br>
### Roles :<br>
Roles control the data visibility in Salesforce's role hierarchy. It's used for sharing settings and reporting.<br><br>
### Permission Sets :<br>
Permission Sets grant additional permissions to users without changing their profile.<br><br>
 
### Validation Rules :<br>
Validation Rules ensure data entered meets business criteria.<br>
Example:<br>
•	Email must contain @gmail.com<br>
•	Stock cannot be negative<br>

### Email Templates :<br>
Predefined formats for sending emails to customers or users.<br>
Example:<br>
•	"Order Confirmation" template<br>
 <img width="868" height="189" alt="image" src="https://github.com/user-attachments/assets/7f3dfe35-d7d7-4c5c-b4a5-2b366860578f" /><br><br>


### Email Alerts :<br>
Email Alerts are actions in Flows or Workflow Rules that send emails using predefined templates.<br>
Example:<br> When a loyalty level changes, an email is sent to the customer.<br><br>


 
<img width="866" height="455" alt="image" src="https://github.com/user-attachments/assets/42dd8b89-b28c-4de3-bfb8-fc058ab5f4da" /><br><br>

 
 <img width="866" height="450" alt="image" src="https://github.com/user-attachments/assets/8aaad8c9-01e3-4333-aa76-2548fade3b0f" /><br><br>


<img width="868" height="391" alt="image" src="https://github.com/user-attachments/assets/de169360-e705-416e-8e94-36661bf0bdbe" /><br><br>



### Flows :<br>
Flows automate business logic without code. They can create, update, or send notifications.<br>
Example:<br>
•	Flow triggers email alerts on new order<br><br>
### Apex :<br>
Apex is Salesforce's object-oriented programming language. It allows developers to write custom logic.<br>
Example: <br>Triggers:<br>
•	Update Total_Amount_of in order<br>
•	Reduce inventory stock<br><br>

## CONCLUSION<br>
The HandsMen Threads CRM system built on Salesforce successfully streamlines key business processes like customer management, product cataloging, order processing, inventory tracking, and loyalty program automation. By leveraging Salesforce tools like Custom Objects, Flows, Validation Rules, and Apex, the system ensures accurate data entry, real-time updates, and enhanced customer experience. Through automation and well-structured user roles, the platform minimizes manual errors, speeds up operations, and provides better insights into sales and stock.

