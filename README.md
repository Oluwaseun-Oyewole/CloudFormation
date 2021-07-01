#### cloud formation template

#####  Anatomy of a CloudFormation template
    A basic CloudFormation template is structured into five parts: 
    
    1 Format version—The latest template format version is 2010-09-09, and this is currently the only valid value. Specify this; the default is the latest version, which
    will cause problems if a new format version is introduced in the future.
    2 Description—What is this template about?
    3 Parameters—Parameters are used to customize a template with values: for example, domain name, database password.
    4 Resources—A resource is the smallest block you can describe. Examples are a virtual server, a load balancer, or an elastic IP address.
    5 Outputs— An output returns something from your template, such as the public name of an EC2 server.