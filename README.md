curl --request POST `
    --url "https://cpc-common-gateway.get-dzo-products.cpc-info.apps.ift-terra000027-edm.ocp.delta.sbrf.ru/v1/search/efsflinvopstopds" `
    --header "Content-Type: application/json;charset=UTF-8" `
    --header "x-b3-traceid: 3c22fe32bf76ef4579bf9632bbe79670" `
    --header "x-synapse-rqtm: 2023-12-14T17:40:13Z" `
    --header "x-synapse-rquid: 1111fe32bf76ef4579bf9632bbe740c4" `
    --header "x-synapse-scname: INV_NPF_OPSTOPDS" `
    --cert "C:\path\to\certificate.crt" `
    --key "C:\path\to\private.key" `
    --data '{ 
        "epkid": "194282260234929456",
        "acctType": [
            "PDS"
        ]
    }'
