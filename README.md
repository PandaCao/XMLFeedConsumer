# XMLFeedConsumer
</br><h2>Java application which:</h2>
<ul>
  <li></br>Gets parameter when executing from commandline (as input parameter)</li>
  <li></br>The parameter contains path to configuration text file</li>
  <li></br>Configuration file has typical *.INI file format  attribute=value</li>
  <li></br>Configuration file contains URL, where your application needs to connect and download a response (the response contains huge XML file) – and connection details needed to connect to DB.</li>
  <li></br>Application takes this received XML data, parses through the data and saves the data to a DB table.</li>
  <li></br>DB can be any SQL DB you select – ideally some hosted DB on public space (free unpaid space) or DB installed on your local PC</li>
  <li></br>There needs to be a track of history of such data, so lets say, that each run if the import to DB will create new data set. If I connect later to DB, I should be able to see data set per timestamp of the application run.</li>
  <li></br>Structure of DB table is up to you. The table should contain all data from the input XML.</li>
  <li></br>The application should have log to a text file, which reflect log level (ERROR, INFO, WARNING, DEBUG).</li>
  <li></br>Don’t forget to report and somehow “cover” cases when input XML suddenly changes (typically one new parameter will appear.</li>
</ul>
