# Urlshort-Redirecting to a Predefined URL

Implemetation of Redirecting to a defined URL from a shortened url(eg:localhost:8080/abcd)

Firstly,decoding the YAML path in the YAMLHandler() and storing the values in an array pathToUrls
Then,moving to MapHandler() where we check if the Urls.Path matches the existing path or not.If found we redirect to the corresponding URL

