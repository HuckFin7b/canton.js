Limiting decimal places of coordinate values in GEOJSON file using notepad++

go to Search > Replace and use these expressions:

in the Find what field:

([0-9]+\.[0-9]{5})([0-9]+)
and in the Replace with field:

\1

Regular expression must be checked