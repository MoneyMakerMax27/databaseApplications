# API Query Building Assignment
---

## USGS Earthquake Queries

### Query 1: [Describe what you're searching for]
**URL:**
```
https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&minmagnitude=3&maxmagnitude=6.0&starttime=2024-01-01&endtime=2024-12-31&limit=10```

**Parameters used:**
- `format`: GeoJSON
- `parameter2`: [minmagnitude]
- `parameter3`: [maxmagnitude]
- `parameter4`: [starttime]
- `parameter5`: [endtime]
- `parameter6`: [limit]




**Result:** [Brief description of what JSON data you got back - how many earthquakes? what magnitude range? etc.]

---

### Query 2: [Describe what you're searching for]
**URL:**
```
https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&orderby=time&maxlongitude&limit=5```

**Parameters used:**
- `format`: GeoJSON
- `parameter2`: [orderby]
- `parameter3`: [maxlongitude]
- `parameter4`: [limit]


**Result:** [Brief description of what JSON data you got back]

---

### Query 3: [Describe what you're searching for]
**URL:**
```
https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&minlatitude=30&maxlatitude=60&limit=10
```

**Parameters used:**
- `format`: GeoJSON
- `parameter2`: [explanation]
- `parameter3`: [explanation]

**Result:** [Brief description of what JSON data you got back]

---

## Open Library Queries

### Query 4: [Describe what you're searching for]
**URL:**
```
https://openlibrary.org/search.json?author=lauren+tarshis&limit=10&fields=title&subject=history&fields=first_publish_year
```

**Parameters used:**
- `format`: GeoJSON
- `parameter2`: [author]
- `parameter3`: [limit]
- `parameter4`: [subject]
- `parameter5`: [fields]

**Result:** [Brief description of what JSON data you got back - how many books found? titles? authors?]


### Query 5: [Describe what you're searching for]
**URL:**
```
https://openlibrary.org/search.json?author=lauren+tarshis&field=first_publish_year&limit=10
```

**Parameters used:**
- `parameter1`: [field]
- `parameter2`: [limit]

**Result:** [Brief description of what JSON data you got back - how many books found? titles? authors?]

### Query 6: [Describe what you're searching for]
**URL:**
```
https://openlibrary.org/search.json?author=lauren+tarshis&lang=eng&field=first_publish_year&limit=10```

**Parameters used:**
- `parameter1`: [lang]
- `parameter2`: [field]
- `parameter2`: [limit]


**Result:** [Brief description of what JSON data you got back - how many books found? titles? authors?]