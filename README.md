# plane-tracker-python
# REAL-TIME Flight Tracker (Romania)

### ABOUT MY PROJECT
This is my first Python project, developed during my 1st year (2nd Semester) at **Economic Informatics**. It is a server-side script that runs on **Linux** and fetches real-time aviation data.

### KEY FEATURES
* *Live Data Fetching*: Connects to the OpenSky Network API to retrieve real-time state vectors.
* *Geographic Filtering*: Precision filtering for the Romanian airspace (Lat/Lon bounding box).
* *SQL Persistence*: Automatically logs every flight into an SQLite database, preventing data loss between runs.
* *Automatic Timestamps*: Each entry is marked with the exact date and time of the observation.
* *Linux Native*: Developed and optimized for Linux environments (Ubuntu/WSL).

### TECH STACKING
* *Language:* Python 3.x
* *Libraries:* `requests` (for API handling)
* *Environment:* Linux (Ubuntu/WSL)
* *Version Control:* Git & GitHub
