# Documentation of Nashbio-ImageVU-API-feasibility-work 

Contacts: Eric.j.olson@vumc.org, james.barclay@vumc.org, karthik.ramadass@vanderbilt.edu

## base64 encoding username:password on linux machines(likely same for MAC)




## CURL command to get data

curl --location -X POST 'https://rd.app.vumc.org/rdws/imagevu/data' --header "Content-Type: application/json" --header 'Authorization: Basic <token_generated>' --data '[5595545051436998434]'
eg: [{"grid":"#######4","accessionNo":"#######","hashedAccessionNo":"5595545051436998434","shiftDays":###}]




