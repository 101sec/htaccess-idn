# htaccess-idn
Based on the untested assumption that Apache, internally, does not explicitly support IDN, but rather passes through any domains that it sees, you could recognize IDNs by the fact that their Punycode-encoded version starts with
`
`
`
xn--
`
`
`
a simple htaccess rule may help Apache servers to block IDN domains. 
Source: https://unix.stackexchange.com/questions/344628/how-to-block-idn-domain-in-htaccess-file   
