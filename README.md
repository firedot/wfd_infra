# wfd_infra
Terraform configuration for AWS Infrastructure for WFD



**ТО DO**

- Create terraform configuration file that:
   - creates two aws EC2 instances:
      - both are CentOS based
      - wfd_client
      - psql_wfd
   - installs PostgreSQL on ```psql_wfd```
   - Creates a DB ```weather_data```
   - creates tables inside DB ```weather_data```
- Put Terraform variables in separate file
- Put Terraform variables in separate file
- Consider putting the DB part in a module
- Create thorough README
