
gpsbabel -w -i kml -f <INPUT_FILE_NAME.kml> -o gpx -F <OUTPUT_FILE_NAME.gpx>


###

AutoExport can export gpx tracks from workouts in iPhone's health app, these gpx files contain waypoints only.

https://www.healthexportapp.com/

```
gpsbabel -i gpx -f file.gpx -x transform,trk=wpt -o gpx -F route1_track.gpx
```
