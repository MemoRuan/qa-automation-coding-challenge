## Prioritized Test Flows:

### User Flow: UI components
#### Priority: Medium

Given the user opens the app  
When the app finish loading  
Then the header is displayed  
And the search form is visible  
And the result section exists  


### User Flow: Header's title
#### Priority: Low

Given the user opens the app   
When the app finish loading  
Then the header displays the title of the app  

### User Flow: Search by using Go button
#### Priority: High

Given the user opens the app   
When the application finish loading  
And the user enters "MemoRuan" in the input text field  
And the user clicks Go button  
Then the repo list is displayed in the results section   

### User Flow: Search by using Enter key
#### Priority: Medium

Given the user opens the app  
When the application finish loading  
And the user enters "Adam.github.io" in the input text field  
And the user press Enter key  
Then the repo list is displayed in the results section  


### User Flow: Basic info displayed 
#### Priority: High

Given the user opens the app  
When the application finish loading  
And the user enters "MemoRuan" in the input text field    
And the user click Go button  
Then a table is displayed with repositories found  
And each row contains a Name column  
And each row contains a Description colum  
And the Description column with no value shows a - sign  


### User Flow: Feedback message "Success"
#### Priority: Medium

Given the user opens the app  
When the application finish loading  
And the user enters "MemoRuan" in the input text field    
And the user click Go button  
Then a "Success!" message is shown above the search field    
And after 5 seconds the feedback message disappears    

### User Flow: Feedback message "Specific Error"
#### Priority: Medium

Given the user opens the app  
When the application finish loading  
And the user enters "Memo.Ruan" in the input text field    
And the user click Go button  
Then a "Github user not found!" message is shown above the search field    
And after 5 seconds the feedback message disappears    

### User Flow: Feedback message "Generic Error"
#### Priority: Medium

Given the user opens the app  
When the application finish loading  
And the user enters "') or ('1'='1--" in the input text field    
And the user click Go button  
Then a generic error message is shown above the search field    
And after 5 seconds the feedback message disappears    
