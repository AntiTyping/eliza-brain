# Setup
### Fish shell

     brew install fish

     You will need to add:
     /usr/local/bin/fish
     to /etc/shells.

     Then run:
     chsh -s /usr/local/bin/fish
     to make fish your default shell.

# iOS
### Convert p12 certificate to pem

     openssl pkcs12 -nodes -clcerts -in certificate.p12 -out certificate.pem

# Data Science
### How to optimize a functino?

* https://www.cvxpy.org/index.html

# Misc

### How to disable active admin filters?

     ActiveAdmin.register Post do
       config.filters = false
     end

# Active Admin

### Add action link to index row

     actions  do |customer|
       item "View2", admin_customer_path(customer)
     end
