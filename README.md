# spring-config-repo

Will represent config file for each customer
{application} -> presents customer folder
    {profile}.yml

Following are other possibilites to represent config file:
/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties

{application} maps to “spring.application.name” on the client side;
{profile} maps to “spring.profiles.active” on the client (comma separated list
{label} which is a server side feature labelling a “versioned” set of config files.
