#### cloudFormation template

##### The anatomy of a cloud template

#####  Format version -- The latest template format version is 2010-09-09 (as of june 2020), and this is currently the only valid value.
##### Description -- This is what your template talks about
##### Parameters -- They are used to customize a template with values e.g domain name, db password etc
##### Resources -- This is the smallest block you can describe e.g virtual servers, ELB, IP address
##### Outputs -- This is like a parameter but it returns something from your template like an public address or your EC2 server

##### Note: ALways specify your format version