# Nounis

Nounis is a reverse-engineered effort of the virtual dean's office platform Verbis.

Currently, it can log in, fetch a user's timetable and display it in a command-line interface: a Flutter GUI supporting mobile and desktop platforms is planned, and possibly other parts of the platform.


## Usage

Clone this repository, ensure you have Python installed, and then install all the requirements.

In the console: `pip install -r requirements.txt`

Now, you can run the `main.py` file with `python main.py`, and authenticate yourself using the interactive interface, though it is strongly suggested to store your credentials in a `.env` file inside the same directory as the `main.py` file, structured as following:
```
LOGIN=<insert your username here>
PASSWORD=<insert your password here>
```
Replace the angle brackets (and the brackets themselves!) with relevant information.

A date range can be input either through command line arguments or interactively.
