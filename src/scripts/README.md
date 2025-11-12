Scripts used by the project

This folder is intended for helper scripts related to data processing and reproducible runs (e.g., CSV cleaners, small ETL helpers, or convenience run scripts).

Suggested usage
- Add small, single-purpose Python scripts (for example `clean_data.py`) and keep them well-documented.
- Example:

```powershell
python src/scripts/clean_data.py --input data/benin.csv --output data/benin_clean.csv
```
