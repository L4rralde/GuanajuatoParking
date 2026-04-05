# Public Parking Buildings in Guanajuato

Recordings of the occupancy of public parking buildings of the State Of Guanajuato.
Gathered from Feb 2025 to Feb 2026.



## Scrapper

Warning. This method might not currently work. That's why no more entries have been appended.

### Installing

Requires git, chrome, python and pip installed.

1. clone this repo

```bash
git clone https://github.com/L4rralde/Parking_Lots.git
cd Parking_Lots
```

2. Create venv

```bash
python -m venv .venv
source .venv/bin/activate
```

3. Install python packages

```bash
pip install -r requirements.txt
```

### How to use

- Run scrapper

```bash
python src/main.py
```

- Update data

```bash
python src/update_data.py
```
