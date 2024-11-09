# Railway Reservation System

This is a simple web application built using Streamlit, a Python library for creating interactive web applications. The application allows users to book railway tickets, view their booking history, and perform other related tasks.

## Features

- **Booking Tickets**: Users can search for available train routes and book tickets.
- **Booking History**: Users can view their past booking history.
- **Cancellation**: Users can cancel their booked tickets.
- **Station Management**: Authorized users can add, update, and delete train stations.
- **Train Management**: Authorized users can add, update, and delete train information.

## Getting Started

To run the application, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/mimi-netizen/railway-reservation-system.git
   ```

2. Change to the `railway-reservation-streamlit-main` directory:

   ```bash
   cd railway-reservation-system/railway-reservation-streamlit-main
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit application:

   ```bash
   streamlit run main.py
   ```

   This will start the application and open it in your default web browser.

## Usage

1. **Book Tickets**: Use the form on the homepage to search for available train routes and book tickets.
2. **View Booking History**: Click on the "Booking History" tab to view your past booking details.
3. **Cancel Bookings**: In the "Booking History" tab, you can cancel your booked tickets.
4. **Manage Stations**: (For authorized users) Use the "Station Management" tab to add, update, and delete train stations.
5. **Manage Trains**: (For authorized users) Use the "Train Management" tab to add, update, and delete train information.

## Technologies Used

- Python
- Streamlit
- SQLite (for the database)

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Create a new pull request, and describe the changes you've made.

## License

This project is licensed under the [MIT License](LICENSE).
