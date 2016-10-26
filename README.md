# draft-immutable
ietf draft on cache-control immutable

rm -f draft.xml ; kramdown-rfc2629 draft.mkd > draft.xml; xml2rfc draft.xml; cat draft.txt; rm draft.xml
