# Public Parking Buildings in Guanajuato

Recordings of the occupancy of public parking buildings of the State Of Guanajuato.
Gathered from Feb 2025 to Feb 2026.


## Relase notes

The attached csv includes the occupancy, from 2025/02/19 (year/month/day) to 2026/02/10 of the following public parking buildings within the Mexican state of Guanajuato:

| Municipality | Name of Parking Lot |
| ------------ | ------------------- |
| Guanajuato   | Alhondiga           |
| Guanajuato   | Alonso              |
| Guanajuato   | Hinojo              |
| Guanajuato   | San Pedro           |
| Guanajuato   | Plaza Pozuelos      |
| Irapuato     | Plaza Hidalgo       |
| Leon         | Plaza del Mariachi  |

For more information about parking lots listed above visit the [site](https://isseg.gob.mx/estacionamientos/).


Depicted by the following charts, you may notice that there's a gap in the third and fourth week. This is because originally the data was provided for homework and I started gathering more data days later using free GitHub workers used for GitHub Actions. Also, as shown in the following plot, the latter data is collected less frequently, mainly because free github actions can't run that frequently and also depends on available free workers.

<div align="center">
<img src="https://github.com/L4rralde/GuanajuatoParking/blob/main/docs/sampling_hist.jpg" width="400"/>

</div>

Finally, as shown in the plot below, I think there were less available workers from 6:00 PM to 8:00 PM. I guess more daily actions using GitHub workers occurs in this time window.

<div align="center">
<img src="https://github.com/L4rralde/GuanajuatoParking/blob/main/docs/sampling.jpg" width="400"/>

</div>


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
