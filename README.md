
Real Estate App Requirements

# FRONTEND PAGES

1. Home
2. About
3. Listings
4. Single Listing
5. Search
6. Register
7. Login
8. Dashboard (Inquiries)

# DESIGN SPECS
1. Use BTRE logo (Frontend and admin)
2. Branding colors – blue(#10284e) green(#30caa0)
3. Mobile Friendly
4. Social media icons & contact info
5. Doesn’t have to be too fancy but must be clean


# FUNCTIONALITY SPECS
1. Manage listings, realtors, contact inquiries and website users via admin
2. Role based users (staff and non-staff)
3. Display listings in app with pagination
4. Ability to set listings to unpublished
5. Search listings by keyword, city, state, bedrooms and price (Homepage & search page)
6. List realtors on about page with “seller of the month” (Control via admin)
7. Listing page should have fields listed below
8. Listing page should have 5 images with lightbox
9. Lightbox should scroll through images
10. Listing page should have a form to submit inquiry for that property listing
11. Form info should go to database and notify realtor(s) with an email
12. Frontend register/login to track inquiries
13. Both unregistered and registered users can submit form. If registered, can only submit one per listing




# LISTING PAGE FIELDS
1. Title
2. Address, city, state, zip
3. Price
4. Bedrooms
5. Bathrooms
6. Square Feet
7. Lot Size
8. Garage
9. Listing Date
10. Realtor – Name & Image
11. Main image and 5 other images




Run Server
```
python manage.py runserver
```

run in the virtual environment
```
source ./venv/bin/activate
```

collect static files
```
python manage.py collectstatic
```
install error psycopg2...
```
pip install psycopg2
pip install psycopg2-binary
```

migrate to check postgresql
```
python manage.py migrate
```
make migrations
```
python manage.py makemigrations
```

install Pillow for use ImageField
```
pip install Pillow 
```

check listing is sql
```
python manage.py sqlmigrate listings 0001
```

create user login
```
python manage.py createsuperuser
```

install pip pylint-django
```
pip install pylint-django
```

install python startapp contact
```
python manage.py startapp contacts
python manage.py makemigrations contacts
python manage.py migrate
```
