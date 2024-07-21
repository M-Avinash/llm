# USER_QUERY = 'how many orders were sent to Germany were delayed in their delivery'
# USER_QUERY = "How many orders sent to germany have freight cost greater than 600 $"
# USER_QUERY = "How many orders have been handled by employeeID 2. How many of those have been delayed in their delivery?"
# USER_QUERY = 'Which orders to Italy have ben processed by employee ID 4'
# USER_QUERY = 'Shipping Partner Ernst Handel has done how many deliveries to Austria. how many of those orders have been delayed in their delivery ?'

These are some of the questions to ask an odata service related to orders having these parameters

    **OrderID:** The unique ID of the order.
    **CustomerID:** The ID of the customer who placed the order.
    **EmployeeID:** The ID of the employee who took the order.
    **OrderDate:** The date the order was placed.
    **RequiredDate:** The date the order is required to be shipped by. RequiredDate will be less than ShippedDate for delayed deliveries.
    **ShippedDate:** The date the order was shipped. RequiredDate will be less than ShippedDate for delayed deliveries.
    **ShipVia:** The ID of the shipper used for the order. 
    **Freight:** The shipping cost of the order.
    **ShipName:** The name of the shipping recipient. This filed can be addressed as shipping partner or Shipper.
    **ShipAddress:** The address of the shipping recipient.
    **ShipCity:** The city of the shipping recipient.
    **ShipRegion:** The region of the shipping recipient (e.g., state or province).
    **ShipPostalCode:** The postal code of the shipping recipient.
    **ShipCountry:** The country of the shipping recipient.
    
    
Give me more such questions to ask this odata service
