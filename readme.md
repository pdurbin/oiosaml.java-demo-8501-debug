# oiosaml.java-demo-8501-debug.war

## Attributes on UserAssertion

    urn:oid:1.3.6.1.4.1.5923.1.1.1.10 (eduPersonTargetedID): [<?xml version="1.0" encoding="UTF-8"?>
    <saml2:NameID xmlns:saml2="urn:oasis:names:tc:SAML:2.0:assertion" Format="urn:oasis:names:tc:SAML:2.0:nameid-format:persistent" NameQualifier="https://idp.testshib.org/idp/shibboleth" SPNameQualifier="pdurbin.pagekite.me">yNZHVwbZQwxl5Kuuultm1+n/jzM=</saml2:NameID>, null]
    urn:oid:1.3.6.1.4.1.5923.1.1.1.1 (eduPersonAffiliation): [Member, Staff]
    urn:oid:0.9.2342.19200300.100.1.1 (uid): [myself]
    urn:oid:2.5.4.3 (cn): [Me Myself And I]
    urn:oid:1.3.6.1.4.1.5923.1.1.1.6 (eduPersonPrincipalName): [myself@testshib.org]
    urn:oid:2.5.4.20 (telephoneNumber): [555-5555]
    urn:oid:1.3.6.1.4.1.5923.1.1.1.9 (eduPersonScopedAffiliation): [Member@testshib.org, Staff@testshib.org]
    urn:oid:1.3.6.1.4.1.5923.1.1.1.7 (eduPersonEntitlement): [urn:mace:dir:entitlement:common-lib-terms]
    urn:oid:2.5.4.42 (givenName): [Me Myself]
    urn:oid:2.5.4.4 (sn): [And I]

- Authenticated: true
- Assertion signed: true
- SAML Profile: false
- OCES Attribute Profile: false
- Persistent Pseudonym Profile: false

## Assertion

    <?xml version="1.0" encoding="UTF-8"?>
    <saml2:Assertion xmlns:saml2="urn:oasis:names:tc:SAML:2.0:assertion" ID="_05fcc693ddb8bf7559ab09f6e16202c0" IssueInstant="2013-11-12T20:58:55.122Z" Version="2.0" xmlns:xs="http://www.w3.org/2001/XMLSchema">
        <saml2:Issuer Format="urn:oasis:names:tc:SAML:2.0:nameid-format:entity">https://idp.testshib.org/idp/shibboleth</saml2:Issuer>
        <ds:Signature xmlns:ds="http://www.w3.org/2000/09/xmldsig#">
            <ds:SignedInfo>
                <ds:CanonicalizationMethod Algorithm="http://www.w3.org/2001/10/xml-exc-c14n#"/>
                <ds:SignatureMethod Algorithm="http://www.w3.org/2000/09/xmldsig#rsa-sha1"/>
                <ds:Reference URI="#_05fcc693ddb8bf7559ab09f6e16202c0">
                    <ds:Transforms>
                        <ds:Transform Algorithm="http://www.w3.org/2000/09/xmldsig#enveloped-signature"/>
                        <ds:Transform Algorithm="http://www.w3.org/2001/10/xml-exc-c14n#">
                            <ec:InclusiveNamespaces xmlns:ec="http://www.w3.org/2001/10/xml-exc-c14n#" PrefixList="xs"/>
                        </ds:Transform>
                    </ds:Transforms>
                    <ds:DigestMethod Algorithm="http://www.w3.org/2000/09/xmldsig#sha1"/>
                    <ds:DigestValue>QC27qsz9ewthgx9bK+ojyMPiRQQ=</ds:DigestValue>
                </ds:Reference>
            </ds:SignedInfo>
            <ds:SignatureValue>LTAQt6jvOymKqH8+2xvFePWW2Wmp6PqkVpu0kzrsZo0/UTdghnLxRzVxluX1D4U/OSoKpUTXc4F1OsSd949lqfgucDVL3TofMa+sDbuquhkhEzSAVWv2P5U0zeFqYB7va7FXhgnafdiiVoeBy031uBWJX3Vra4D4W8LW3ZEih4oouGTndXr7Ko3TN0Jg5MxBgnWIm1kLbrQ0fjGgajMn9NgyC3f3ZOfQ+y17LQxlzuiv3jyVpF3ZekwIOw+02YlScBA3VbSzGk7Di40DV3Egv8lQL7acjGHx3xnZDmCNpfTNcbDEp75FIX4pRJhh6g21Jl9wDfugMFd6/XwABsm9lg==</ds:SignatureValue>
            <ds:KeyInfo>
                <ds:X509Data>
                    <ds:X509Certificate>MIIEDjCCAvagAwIBAgIBADANBgkqhkiG9w0BAQUFADBnMQswCQYDVQQGEwJVUzEVMBMGA1UECBMM
    UGVubnN5bHZhbmlhMRMwEQYDVQQHEwpQaXR0c2J1cmdoMREwDwYDVQQKEwhUZXN0U2hpYjEZMBcG
    A1UEAxMQaWRwLnRlc3RzaGliLm9yZzAeFw0wNjA4MzAyMTEyMjVaFw0xNjA4MjcyMTEyMjVaMGcx
    CzAJBgNVBAYTAlVTMRUwEwYDVQQIEwxQZW5uc3lsdmFuaWExEzARBgNVBAcTClBpdHRzYnVyZ2gx
    ETAPBgNVBAoTCFRlc3RTaGliMRkwFwYDVQQDExBpZHAudGVzdHNoaWIub3JnMIIBIjANBgkqhkiG
    9w0BAQEFAAOCAQ8AMIIBCgKCAQEArYkCGuTmJp9eAOSGHwRJo1SNatB5ZOKqDM9ysg7CyVTDClcp
    u93gSP10nH4gkCZOlnESNgttg0r+MqL8tfJC6ybddEFB3YBo8PZajKSe3OQ01Ow3yT4I+Wdg1tsT
    pSge9gEz7SrC07EkYmHuPtd71CHiUaCWDv+xVfUQX0aTNPFmDixzUjoYzbGDrtAyCqA8f9CN2txI
    fJnpHE6q6CmKcoLADS4UrNPlhHSzd614kR/JYiks0K4kbRqCQF0Dv0P5Di+rEfefC6glV8ysC8dB
    5/9nb0yh/ojRuJGmgMWHgWk6h0ihjihqiu4jACovUZ7vVOCgSE5Ipn7OIwqd93zp2wIDAQABo4HE
    MIHBMB0GA1UdDgQWBBSsBQ869nh83KqZr5jArr4/7b+QazCBkQYDVR0jBIGJMIGGgBSsBQ869nh8
    3KqZr5jArr4/7b+Qa6FrpGkwZzELMAkGA1UEBhMCVVMxFTATBgNVBAgTDFBlbm5zeWx2YW5pYTET
    MBEGA1UEBxMKUGl0dHNidXJnaDERMA8GA1UEChMIVGVzdFNoaWIxGTAXBgNVBAMTEGlkcC50ZXN0
    c2hpYi5vcmeCAQAwDAYDVR0TBAUwAwEB/zANBgkqhkiG9w0BAQUFAAOCAQEAjR29PhrCbk8qLN5M
    FfSVk98t3CT9jHZoYxd8QMRLI4j7iYQxXiGJTT1FXs1nd4Rha9un+LqTfeMMYqISdDDI6tv8iNpk
    OAvZZUosVkUo93pv1T0RPz35hcHHYq2yee59HJOco2bFlcsH8JBXRSRrJ3Q7Eut+z9uo80JdGNJ4
    /SJy5UorZ8KazGj16lfJhOBXldgrhppQBb0Nq6HKHguqmwRfJ+WkxemZXzhediAjGeka8nz8Jjwx
    pUjAiSWYKLtJhGEaTqCYxCCX2Dw+dOTqUzHOZ7WKv4JXPK5G/Uhr8K/qhmFT2nIQi538n6rVYLeW
    j8Bbnl+ev0peYzxFyF5sQA==</ds:X509Certificate>
                </ds:X509Data>
            </ds:KeyInfo>
        </ds:Signature>
        <saml2:Subject>
            <saml2:NameID Format="urn:oasis:names:tc:SAML:2.0:nameid-format:transient" NameQualifier="https://idp.testshib.org/idp/shibboleth">_0040babf59f9ae294e3bacae2bf3e433</saml2:NameID>
            <saml2:SubjectConfirmation Method="urn:oasis:names:tc:SAML:2.0:cm:bearer">
                <saml2:SubjectConfirmationData Address="140.247.0.43" InResponseTo="_ed76b979-34d3-46c2-a22a-e63f080913f8" NotOnOrAfter="2013-11-12T21:03:55.122Z" Recipient="http://pdurbin.pagekite.me/oiosaml.java-demo-8501-debug/saml/SAMLAssertionConsumer"/>
            </saml2:SubjectConfirmation>
        </saml2:Subject>
        <saml2:Conditions NotBefore="2013-11-12T20:58:55.122Z" NotOnOrAfter="2013-11-12T21:03:55.122Z">
            <saml2:AudienceRestriction>
                <saml2:Audience>pdurbin.pagekite.me</saml2:Audience>
            </saml2:AudienceRestriction>
        </saml2:Conditions>
        <saml2:AuthnStatement AuthnInstant="2013-11-12T20:58:55.024Z" SessionIndex="_90f9df17366c56ab5abfd6fb02063c29">
            <saml2:SubjectLocality Address="140.247.0.43"/>
            <saml2:AuthnContext>
                <saml2:AuthnContextClassRef>urn:oasis:names:tc:SAML:2.0:ac:classes:PasswordProtectedTransport</saml2:AuthnContextClassRef>
            </saml2:AuthnContext>
        </saml2:AuthnStatement>
        <saml2:AttributeStatement>
            <saml2:Attribute FriendlyName="uid" Name="urn:oid:0.9.2342.19200300.100.1.1" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">myself</saml2:AttributeValue>
            </saml2:Attribute>
            <saml2:Attribute FriendlyName="eduPersonAffiliation" Name="urn:oid:1.3.6.1.4.1.5923.1.1.1.1" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">Member</saml2:AttributeValue>
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">Staff</saml2:AttributeValue>
            </saml2:Attribute>
            <saml2:Attribute FriendlyName="eduPersonPrincipalName" Name="urn:oid:1.3.6.1.4.1.5923.1.1.1.6" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">myself@testshib.org</saml2:AttributeValue>
            </saml2:Attribute>
            <saml2:Attribute FriendlyName="sn" Name="urn:oid:2.5.4.4" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">And I</saml2:AttributeValue>
            </saml2:Attribute>
            <saml2:Attribute FriendlyName="eduPersonScopedAffiliation" Name="urn:oid:1.3.6.1.4.1.5923.1.1.1.9" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">Member@testshib.org</saml2:AttributeValue>
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">Staff@testshib.org</saml2:AttributeValue>
            </saml2:Attribute>
            <saml2:Attribute FriendlyName="givenName" Name="urn:oid:2.5.4.42" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">Me Myself</saml2:AttributeValue>
            </saml2:Attribute>
            <saml2:Attribute FriendlyName="eduPersonEntitlement" Name="urn:oid:1.3.6.1.4.1.5923.1.1.1.7" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">urn:mace:dir:entitlement:common-lib-terms</saml2:AttributeValue>
            </saml2:Attribute>
            <saml2:Attribute FriendlyName="cn" Name="urn:oid:2.5.4.3" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">Me Myself And I</saml2:AttributeValue>
            </saml2:Attribute>
            <saml2:Attribute FriendlyName="eduPersonTargetedID" Name="urn:oid:1.3.6.1.4.1.5923.1.1.1.10" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue>
                    <saml2:NameID Format="urn:oasis:names:tc:SAML:2.0:nameid-format:persistent" NameQualifier="https://idp.testshib.org/idp/shibboleth" SPNameQualifier="pdurbin.pagekite.me" xmlns:saml2="urn:oasis:names:tc:SAML:2.0:assertion">yNZHVwbZQwxl5Kuuultm1+n/jzM=</saml2:NameID>
                </saml2:AttributeValue>
            </saml2:Attribute>
            <saml2:Attribute FriendlyName="telephoneNumber" Name="urn:oid:2.5.4.20" NameFormat="urn:oasis:names:tc:SAML:2.0:attrname-format:uri">
                <saml2:AttributeValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:type="xs:string">555-5555</saml2:AttributeValue>
            </saml2:Attribute>
        </saml2:AttributeStatement>
    </saml2:Assertion>