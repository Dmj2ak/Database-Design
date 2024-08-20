# Data Modelling/Database-Design
Designing a database schema  for  A Real Estate Investment business  designing a new application using the information below to determine the data elements, completing the normalization process, creating an ERD, and building a schema in an Oracle database using SQL.



Business Requirements

	• The new application will support all the business operations; this includes maintaining records of buyers, properties acquired, contractors, sales agent, agreements, and employees.  Over the years there has been thousands of properties acquired and sold. Staff members have worked with a number of contractors consisting of Interior Designers and General Contractors.  The business also employs five employees (accountant, lawyers, secretary, and two maintenance worker). In addition, over the years the company has worked with several independent Real Estate Sales Agents.
	• The database should contain details from previous and potential buyers including account number, name, address, contact info, occupation, salary, and credit score.
	• You also need to maintain Employee details employer code, employer name, employer address, employer phone number, etc...
	• It should also contain data for contractors such as id, name, address, phone number. In addition, you also need to include sales agents id, name, address, phone number.
	• You also should maintain data for contract agreements between various contractors and the company (Real Estate Investment business ).  These agreements should include an agreement number, contractor id, contractor name, contractor address, contractor phone number, and a description of the agreement.
	• A contractor can enter into several agreements, but each agreement can only be associated with one contractor. 
	• Lastly, the database schema should contain all the properties acquired and sold, each property should have a parcel number, address, specification such as the number of rooms, square feet, purchase date, purchase amount, and market value, and architecture style description. The architectural styles include Cope Code, Colonial Contemporary, Ranch and etc… For the architecture style description, you need to store information such as the style and description of each style to provide additional characteristics for each property.
	• The property should also be associated with details for both the buyer and sales agent (id, name, address, phone).
	•  Also noted that a buyer can purchase one or more properties from the Real Estate Investment business and the property can have one or more buyers.
	• The sale of a property can be conducted by one agent, but an agent can sale many properties. 
	•  Based on your evaluation, identify all the data elements required to build a database schema, you are welcome to add additional attributes if you see fit…


