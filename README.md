# Database-Design
Build a new application that will support all the business operations; this includes maintaining records of buyers, properties acquired, contractors, sales agent, agreements, and employees.


Background
Over the years there has been thousands of properties acquired and sold. Staff members have worked with a number of contractors consisting of Interior Designers and General Contractors.  Your business also employs five employees (accountant, lawyers, secretary, and two maintenance worker). In addition, over the years the business has worked with several independent Real Estate Sales Agents.

The  database should contain details from previous and potential buyers including account number, name, address, contact info, occupation, salary, and credit score.
You also need to maintain Employee details employer code, employer name, employer address, employer phone number, etc...
It should also contain data for contractors such as id, name, address, phone number. In addition, you also need to include sales agents id, name, address, phone number.
Maintain data for contract agreements between various contractors and your company.  These agreements should include an agreement number, contractor id, contractor name, contractor address, contractor phone number, and a description of the agreement.
A contractor can enter into several agreements, but each agreement can only be associated with one contractor. 
Lastly, the database schema should contain all the properties acquired and sold, each property should have a parcel number, address, specification such as the number of rooms, square feet, purchase date, purchase amount, and market value, and architecture style description. The architectural styles include Cope Code, Colonial Contemporary, Ranch and etc… For the architecture style description, you need to store information such as the style and description of each style to provide additional characteristics for each property.
The property should also be associated with details for both the buyer and sales agent (id, name, address, phone).
It is noted that a buyer can purchase one or more properties from you and the property can have one or more buyers.
The sale of a property can conducted by one agent, but an agent can sale many properties. 

