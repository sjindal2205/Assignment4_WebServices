# Assignment4_WebServices

1) GET /web/fetchCustomers

Description: This API calls another REST Mule Application and returns the list of customers

2) POST /web/checkCountryCapital

Description: This API consumes a SOAP webservice and returns the Country's capital on the basis of countryISOCode passed

Payload:
{
	"countryISOCode": "IND"
}

3) POST /web/errorHandling

Description: This API handles error scenarios and mask the sensitive information.

Payload:
{
    "Name": "Srinivas",
    "accno": "1234567",
    "age": 30,
    "ssn": "1234567"
}
