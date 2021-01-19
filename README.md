Python Program

WeCare insurance company wants to calculate premium of vehicles.
Vehicles are of two types – "Two Wheeler" and "Four Wheeler". Each vehicle is identified by vehicle id, type, cost and premium amount. Premium amount is 2% of the vehicle cost for two wheelers and 6% of the vehicle cost for four wheelers.

Details of Class :

ClassNameVehicle
Attributesvehicle_cost
vehicle_type
premium_amount
vehicle_id
Methodscalculate_premium()
__init__(self, vehicle_type, vehicle_id,vehicle_cost)
display_vehicle_details() : Display the type of vehicle, cost and premium amount.
Write a Python program to implement the class with its attributes and methods.
Note:
1. Consider all instance variables to be private and methods to be public
2. Include getter and setter methods for all instance variables
3. take vehicle type and vehicle cost from the user.
4. Create an object of the Vehicle and initialize all the details of the object through the constructor and  Calculate the premium amount and display the vehicle    details(vehicle type, vehicle cost, and the premium amount ) of the vehicle.
Input1: TwoWheeler
50000
Output1:TwoWheeler 50000 1000
Input2: FourWheeler
500000
Output2: FourWheeler 500000 30000
