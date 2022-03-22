# Documentation of Nashbio-ImageVU-API-feasibility-work 

Contacts: Eric.j.olson@vumc.org, james.barclay@vumc.org, karthik.ramadass@vanderbilt.edu

## base64 encoding username:password on linux machines(likely same for MAC)

$ echo -n 'username:password' | base64  #You may get creds from Eric Olson


## CURL command to get data

$ curl --location -X POST 'https://rd.app.vumc.org/rdws/imagevu/data' --header "Content-Type: application/json" --header 'Authorization: Basic <token_generated>' --data '[5595545051436998434]'

eg: [{"grid":"#######4","accessionNo":"#######","hashedAccessionNo":"5595545051436998434","shiftDays":###}]

## CURL command to push to ambra

$ curl --location -X POST 'https://rd.app.vumc.org/rdws/imagevu/push/nashbio' --header "Content-Type: application/json" --header 'Authorization: Basic <token_generated>' --data '[5595545051436998434]'

eg: {"5595545051436998434":"PUSHED"}



