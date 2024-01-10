# GoLang-1.6-App
This is a simple Go language program that contains a JSON Injection vulnerability.

After successful completion of the scan using FOD, you should see a JSON Injection vulnerability in the analysis results. Other categories of issues might also be present, depending on the Fortify Rulepacks used in the scan.
The JSON Injection vulnerability shows that the tainted data from user input is saved to an embedded file as a JSON object. Data is then decoded from an embedded file and, eventually, function json.Marshal() is called.
