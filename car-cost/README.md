# Determining the cost of cars

*Used car sales service "Not beaten, not beautiful" is developing an application to attract new customers. In it, you can quickly find out the market value of your car. At your disposal are historical data: technical specifications, equipment and prices of cars. You need to build a model to determine the cost.*

***Important to the customer:***
- quality of prediction;
- prediction speed;
- studying time.

1. Loading and preparing data.
2. Training of different models.
3. Analyze the speed of work and the quality of the models.

***Data Description***
*Signs*
- DateCrawled - date of downloading the profile from the database
- VehicleType - type of car body
- RegistrationYear — year of car registration
- Gearbox - type of gearbox
- Power - power (hp)
- Model - car model
- Kilometer - mileage (km)
- RegistrationMonth — month of car registration
- FuelType — type of fuel
- Brand - car brand
- NotRepaired - was the car under repair or not
- DateCreated — date of creation of the questionnaire
- NumberOfPictures - the number of photos of the car
- PostalCode - postal code of the owner of the profile (user)
- LastSeen - date of last user activity
*Target feature*
- Price - price (EUR)
