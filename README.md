# cert-info

A tool to check the certificate of a domain.

## Usage

```
user@Computer:~/Projects/cert-info$ cert-info example.com
{'OCSP': ('http://ocsp.digicert.com',),
 'caIssuers': ('http://cacerts.digicert.com/DigiCertSHA2HighAssuranceServerCA.crt',),
 'crlDistributionPoints': ('http://crl3.digicert.com/sha2-ha-server-g4.crl',
                           'http://crl4.digicert.com/sha2-ha-server-g4.crl'),
 'issuer': ((('countryName', 'US'),),
            (('organizationName', 'DigiCert Inc'),),
            (('organizationalUnitName', 'www.digicert.com'),),
            (('commonName', 'DigiCert SHA2 High Assurance Server CA'),)),
 'notAfter': 'Nov 28 12:00:00 2018 GMT',
 'notBefore': 'Nov  3 00:00:00 2015 GMT',
 'serialNumber': '0E64C5FBC236ADE14B172AEB41C78CB0',
 'subject': ((('countryName', 'US'),),
             (('stateOrProvinceName', 'California'),),
             (('localityName', 'Los Angeles'),),
             (('organizationName',
               'Internet Corporation for Assigned Names and Numbers'),),
             (('organizationalUnitName', 'Technology'),),
             (('commonName', 'www.example.org'),)),
 'subjectAltName': (('DNS', 'www.example.org'),
                    ('DNS', 'example.com'),
                    ('DNS', 'example.edu'),
                    ('DNS', 'example.net'),
                    ('DNS', 'example.org'),
                    ('DNS', 'www.example.com'),
                    ('DNS', 'www.example.edu'),
                    ('DNS', 'www.example.net')),
 'version': 3}

```
