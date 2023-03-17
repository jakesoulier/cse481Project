## Welcome to our tracking app

### Tasks:

* Data exchange design
* Data flow design
* OTP behavior methods stubbed out
* Unit test EUNIT meck isolated

### Design

![store_package_info](https://user-images.githubusercontent.com/97404870/224755510-1953ea42-b9fd-409a-af9c-482ccf35e7dc.png)

![query_package_history](https://user-images.githubusercontent.com/97404870/224755847-e1111e1d-1ca2-4317-bc89-df42d9a8421e.png)

![store_vehicle_info](https://user-images.githubusercontent.com/97404870/224756052-996132f0-6d89-4758-8383-9f8bc899b82e.png)

![query_vehicle_history](https://user-images.githubusercontent.com/97404870/224756275-5be76f78-d53a-464b-845e-ef01eb222f38.png)

![store_facility_info](https://user-images.githubusercontent.com/97404870/224756567-a96f9a9d-1706-4e79-b984-05f9ddddda22.png)

![query_facility](https://user-images.githubusercontent.com/97404870/224756733-cfa6bf26-4e46-4c21-8559-5e73d4659985.png)

### System requirements

Add mock to rebar.config: 
```
{profiles, [{test, [{deps, [meck]}]}]}
```
