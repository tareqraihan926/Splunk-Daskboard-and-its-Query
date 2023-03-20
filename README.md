# Splunk-Daskboard-and-its-Query

**Dashboard Query for find all coloumns**

      sourcetype="splunk.csv"
      | table "Receive Time", Type, "From Zone", "To Zone", "extracted_Source", "NAT DEST IP",
      "NAT SOurce IP", Destination, "To Port", Application, Action, Rule, "Session End Reason",
      Bytes, "HTTP_2 Connection Session ID"
