Hi,

I found a reflected XSS on `[]`.


## Description

The parameter `yyy` is missing sanitization in the following url:  
`[]`

Payload:  
`.......`


## PoC

1- Open the following link
```
```
2- XSS will trigger

[ss]


## Risk

- hostile code insertion
- session hijacking
- user browser corruption


## Remediation

- encode special characters like `'` `"` `<` `>`


## See also

https://www.owasp.org/index.php/Top_10_2013-A3-Cross-Site_Scripting_(XSS)


Best regards,

@Splint3r7
