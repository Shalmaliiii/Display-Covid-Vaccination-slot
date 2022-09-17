# **Displaying Vaccination slots**

The user can search location of the nearest vaccination center & vaccine details by entering his State and corresponding District. Moreover the user can filter slots according to the date. The data is being fetched by real time APIs. <br>

Api used for fetching slots :<br>
https://cdn-api.co-vin.in/api/v2/appointment/sessions/public/calendarByDis
trict?district_id=

Api used to fetch ID of districts :<br>
https://cdn-api.co-vin.in/api/v2/admin/location/districts/

---
### Overview:<br>
- Search slots in range of 5 days from the chosen date : 

![](/images/page1.png)

- Search slots only on the chosen date : 

![](/images/page2.png)

- If there is no availability of dose, the field is marked in red else - green  :

![](/images/page3.png)

