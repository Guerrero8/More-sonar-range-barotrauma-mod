~~~
curl -X POST "https://cpc-common-gateway-get-dzo-products.cpc-info.apps.ift-terra000027-edm.ocp.delta.sbrf.ru/v1/search/efsinvostopds" \
--header "Content-Type: application/json;charset=utf-8" \
--header "synapse-uuid: 1111f52fb7f6e457fb9632be7a07c4c1" \
--header "synapse-scenario: IN" \
--data '{ "field": "pps" }' \
--cert "c:/юзер/22698452/myCert/Insomni/CI01871805.crt" \
--key "c:/юзер/22698452/myCert/Insomni/CI01871805.key"
