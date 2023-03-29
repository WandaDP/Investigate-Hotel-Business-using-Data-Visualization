# Python : Investigate Hotel Business using Data Visualization

Hotel is one of the most important tourism industry accommodation. To improve hotel business performance we need to explore and analyze the data. 
This study case focus on data exploration to determine customer behavior in making hotel reservations and its relationship to the impact of hotel booking cancellations. We will present the insights with data visualization to make it easier understand data.

### Dataset
hotel_bookings_data.csv 
- hotel : Types of Hotels (City Hotel & Resort Hotel)
- is_canceled : Indicates reservation is canceled (1) or not (0)
- lead_time : Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
- arrival_date_year : arrival year
- arrival_date_month : arrival month
- arrival_date_week_number : Week number of the arrival date
- arrival_date_day_of_month : Day of the month of the arrival date
- stays_in_weekend_nights : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
- stays_in_weekdays_nights : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.
- adults : Number of adults
- children : Number of children
- babies : Number of babies
- meal : Type of ordered meal (no meal / breakfast/ dinner/ full board/ undefined)
- city : City of origin
- market_segment : Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
- distribution_channel : Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
- is_repeated_guest : Value indicating if the booking name was from a repeated guest (1) or not (0)
- previous_cancellations : Number of previous bookings that were canceled by the customer prior to the current booking
- previous_bookings_not_canceled : Number of previous bookings not canceled by the customer prior to the current booking
- booking_changes : Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
- deposit_type : Indicates whether the customer has a guarantee with a deposit. No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.
- agent : ID of the travel agency that made the booking
- company : ID of the company/entity that made the booking or responsible for paying the booking.
- days_in_waiting_list : Number of days the booking was in the waiting list before it was confirmed to the customer
- customer_type : Types of customers. (Personal/ Family/ Contract/ Business)
- adr : Average Daily Rate (Calculated by dividing the sum of all lodging transactions by the total number of staying nights)
- required_car_parking_spaces : Number of car parking spaces required by the customer
- total_of_special_requests : Number of special requests made by the customer.
- reservation_status : Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why

### Tools
- Programming Language : Python
- Python Library : Pandas & Numpy
- Visualization : Matplotlib & Seaborn 

### Data Preprocessing
1.1 Handle Missing Value
1.2 Handle Incorrect Data Type
1.3 Handle Unsuitable Values
1.4 Remove Unnecessary Data

### Data Visualization
