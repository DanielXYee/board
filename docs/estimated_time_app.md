# Estimated Time Tracking Plugin Installation

## Estimated Time Tracking Plugin Installation

[![How to configure Estimated Time Tracking plugin](estimated_time.png)](https://www.youtube.com/watch?v=uVYVskj3BJM)

1.  Goto your Restyaboard installation root directory. e.g., directory: "/usr/share/nginx/html/restyaboard/"
2.  Extract/unzip the purchased plugin zip into the restyaboard installation path. e.g., "/usr/share/nginx/html/restyaboard/"
3.  Give file permission to extracted files. e.g., "chmod -R 0777 client/apps/r_estimated_time/"
4.  Execute the sql file in "client/apps/r_estimated_time/sql/r_estimated_time.sql" using the command "psql -h localhost -d {DATABASE_NAME} -U {USER_Name} -w < /usr/share/nginx/html/restyaboard/client/apps/r_estimated_time/sql/r_estimated_time.sql"
5.  After above process, clear the browser cache and login again to view the installed Estimated Time Tracking plugins on your Restyaboard.
