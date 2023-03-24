# Reservation Cancellation Prediction
![RC](https://user-images.githubusercontent.com/108439954/222217456-92356fc5-e97c-4022-9312-ffb412e52608.png)

# Kaggle Notebook Link
https://www.kaggle.com/code/moohamedelsayed/reservation-cancellation-prediction

## Dataset Description
Customer behavior and booking possibilities have been radically changed by online hotel reservation channels. Cancellations or no-shows cause a significant number of hotel reservations to be canceled. Cancellations can be caused by a variety of factors, such as scheduling conflicts, changes in plans, etc. In many cases, this is made easier by the possibility of doing so free or at a low cost, which is beneficial for hotel guests but less desirable and possibly revenue-diminishing for hotels.

The goal is to build a Machine Learning model to help the Hotel Owners better understand if the customer is going to honor the reservation or cancel it ?  

## The file contains the different attributes of customers' reservation details. The detailed data dictionary is given below  

### Input variables :  
1- Booking_ID - unique identifier of each booking  
2- No of adults - Number of adults  
3- No of children - Number of Children  
4- noofweekend_nights - Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel  
5- noofweek_nights - Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel  
6- typeofmeal_plan - Type of meal plan booked by the customer  
7- requiredcarparking_space - Does the customer require a car parking space? (0 - No, 1- Yes)  
8- roomtypereserved - Type of room reserved by the customer. The values are ciphered (encoded) by INN Hotels.  
9- lead_time - Number of days between the date of booking and the arrival date  
10- arrival_year - Year of arrival date  
11- arrival_month - Month of arrival date  
12- arrival_date - Date of the month  
13- Market segment type - Market segment designation.  
14- repeated_guest - Is the customer a repeated guest? (0 - No, 1- Yes)  
15- noofprevious_cancellations - Number of previous bookings that were canceled by the customer prior to the current booking  
16- noofpreviousbookingsnot_canceled - Number of previous bookings not canceled by the customer prior to the current booking  
17- avgpriceper_room - Average price per day of the reservation; prices of the rooms are dynamic. (in euros)  
18- noofspecial_requests - Total number of special requests made by the customer (e.g. high floor, view from the room, etc)  

## Output variable :  
19- booking_status - Flag indicating if the booking was canceled or not.  


## Objective:  
Understand the Dataset & cleanup.    
Build classification model to predict whether the booking was canceled or not.  
Also fine-tune the hyperparameters & compare the evaluation metrics of various algorithms.
