# Explore US Bikeshare Data

This project is an interactive Python command-line application that explores
bikeshare usage data from three major US cities — **Chicago, New York City,
and Washington**. It lets the user filter the data by **city, month, and day
of week**, then computes and displays descriptive statistics on the trips,
including popular travel times, popular stations and trips, trip duration,
and user information.

## Information about how to use your project

### Dependencies

- Python 3.x
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)

Install the dependencies:

```bash
pip install pandas numpy

### Data files

The following data files must be present in the project directory
(they are not tracked in git):

- `chicago.csv`
- `new_york_city.csv`
- `washington.csv`

### Running the project

```bash
python bikeshare_starter.py
```

Follow the prompts to choose a city, month, and day. Enter `all` to apply no
month/day filter. When asked to restart, enter `yes` to run again or anything
else to quit.

### Common issues and troubleshooting

- **`FileNotFoundError`** — make sure the `.csv` data files are in the same
  directory as the script.
- **Missing `Gender` / `Birth Year` stats** — the Washington dataset does not
  include these columns, so those statistics are skipped for that city.


## Contribution guidelines

This is a learning project submitted as part of the Udacity *Programming for
Data Science with Python* Nanodegree. Suggestions and improvements are welcome —
please open an issue or submit a pull request.

## Credits

- [Udacity – Programming for Data Science with Python Nanodegree](https://www.udacity.com/course/programming-for-data-science-nanodegree--nd104)
- Bikeshare data provided by [Motivate](https://www.motivateco.com/), a bike share system provider.

## Date created

July 4, 2026