# htaccess-idn
Based on the untested assumption that Apache, internally, does not explicitly support IDN, but rather passes through any domains that it sees, you could recognize IDNs by the fact that their Punycode-encoded version starts with 
`
`
`
xn--
`
`
`
