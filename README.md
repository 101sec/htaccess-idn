# htaccess-idn
Based on the untested assumption that Apache, internally, does not explicitly support IDN, but rather passes through any domains that it sees, you could recognize IDNs by the fact that their Punycode-encoded version starts with
`
`
`
xn--
`
`
`

Therefore, a simple htaccess rule may help protect Apache servers by blocking IDN domains and subsites (HTTP & HTTPS) . 

Source: https://unix.stackexchange.com/questions/344628/how-to-block-idn-domain-in-htaccess-file   
