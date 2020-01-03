
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
•	Manage listings, realtors, contact inquiries and website users via admin
•	Role based users (staff and non-staff)
•	Display listings in app with pagination
•	Ability to set listings to unpublished
•	Search listings by keyword, city, state, bedrooms and price (Homepage & search page)
•	List realtors on about page with “seller of the month” (Control via admin)
•	Listing page should have fields listed below
•	Listing page should have 5 images with lightbox
•	Lightbox should scroll through images
•	Listing page should have a form to submit inquiry for that property listing
•	Form info should go to database and notify realtor(s) with an email
•	Frontend register/login to track inquiries
•	Both unregistered and registered users can submit form. If registered, can only submit one per listing



LISTING PAGE FIELDS

•	Title
•	Address, city, state, zip
•	Price
•	Bedrooms
•	Bathrooms
•	Square Feet
•	Lot Size
•	Garage
•	Listing Date
•	Realtor – Name & Image
•	Main image and 5 other images

Possible Future Functionality
•	Google maps on listing page
•	Buyer testimonials





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
