   COVID-19 Hospital Bed Slot Booking System

During the COVID-19 pandemic, finding a free hospital bed was one of the hardest things for patients and their families. People often had to call hospital after hospital just to find out whether a bed was available. I built this project to make that process simpler.

This is a web app where users can check bed availability and book a slot online, and hospitals can manage their capacity in one place.

## What it does

- Shows real-time bed availability across hospitals
- Lets patients book a bed slot online
- Lets hospital staff update bed counts and manage bookings
- Stores all records in a MySQL database so data stays organized and consistent
- Keeps the interface simple, so anyone can use it, even under stress

## Built with

- **Backend:** Python
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript

## Getting started

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/covid-bed-booking.git
   cd covid-bed-booking
   ```

2. Install the dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the database
   - Create a MySQL database (for example, `covid_beds`)
   - Import the SQL file included in the project
   - Update your database username and password in the config file

4. Run the app
   ```bash
   python app.py
   ```

5. Open your browser and go to `http://localhost:5000`

## What I learned

This project taught me a lot about connecting a Python backend to a real database, handling user bookings without conflicts, and designing pages that are easy to use. It also showed me how technology can help in a real crisis.

## Future improvements

- SMS or email confirmation after booking
- A search filter by city, hospital, or bed type (ICU, oxygen, general)
- An admin dashboard with charts showing bed usage

## Author

**[Abhinay kumar]**
- The `git clone` link (your username and repo name)
- `app.py`, the port `5000` and the SQL file name, so they match your project. I assumed Flask's usual defaults; tell me if you used something else, like Django.
- Your name and profile links
