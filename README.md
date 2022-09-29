### Designed and developed by ASHISH DANDADE
### Homepage
![homepage snap](https://github.com/ashishdandade/insurance_webapp/blob/master/static/image/homepage.png?raw=true)
### Admin Dashboard
![dashboard snap](https://github.com/ashishdandade/insurance_webapp/blob/master/static/image/admin.png?raw=true)
### Policy 
![policy snap](https://github.com/ashishdandade/insurance_webapp/blob/master/static/image/policy.png?raw=true)
### User
![user snap](https://github.com/ashishdandade/insurance_webapp/blob/master/static/image/user.png?raw=true)
## Functions 
### Admin
- Admin account can be created using createsuperuser command.
- After login, admin can view/update/delete customer
- Can view/add/update/delete policy category like Life, Health, Motor, Travel
- Can view/add/update/delete policy
- Can view total policy holder, approved policy holder, disapproved policy holder
- Can approve policy, applied by customer
- Can answer customer question

### Customer
- Create account (no approval required by admin)
- After login, can view all policy that are added by admin.
- If customer likes any policy, then they can apply for it.
- When customer will apply for any policy, it will go into pending status, admin can approve it.
- Customer can check status of his policy under history section
- Customer can ask question from admin. 

---

py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
