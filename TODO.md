mruby-ldns
======

- http://docs.ruby-lang.org/ja/2.1.0/library/resolv.html

## implementation list
checked methods is implemented  
  
### method                
| Resolv class          | implemented?  |   
|:---------------------:|:-:| 
| Resolv.each_address   |  |   
| Resolv.each_name      |  |   
| Resolv.getname        | ok |   
| Resolv.getnames       |  |   
| Resolv#getadress      | ok|   
| Resolv#getaddresses   |  |   

| Resolv::DNS class    |  |   
|---------------------:|:-:| 
| DNS.new               |  |   
| DNS.open              |  |   
| DNS#close             |  |   
| DNS#each_address      |  |   
| DNS#each_name         |  |   
| DNS#each_resource     |  |   
| DNS#getadress         |  |   
| DNS#getaddresses      |  |   
| DNS#getname           |  |   
| DNS#getnames          |  |   
| DNS#getresource       |  |   
| DNS#getresources      |  |   
| DNS#timeouts=         |  |   

| class implementation              |  |   
|---------------------:|:-:| 
| Resolv::DNS::Resource             |  |   
| Resolv::DNS::Resource#IN::A       |  |   
| Resolv::DNS::Resource#IN::AAAA    |  |   
| Resolv::DNS::Resource#IN::PTR     |  |   
| Resolv::DNS::Resource#IN::NS      |  |   
| Resolv::DNS::Resource#IN::ANY     |  |   
| Resolv::DNS::Resource#IN::MX      |  |   
| Resolv::DNS::Resource#IN::CNAME   |  |   
| Resolv::DNS::Resource#IN::TXT     |  |   
| Resolv::DNS::Resource#IN::SOA     |  |   

| class impl | |
|---------------------:|:-:| 
| Resolv::Host  |   |
| Resolv::IPv4  |   |
| Resolv::IPv4.address | |
| Resolv::IPv6  |   |

| module                            |  |   
|---------------------:|:-:| 
| Resolv::DNS::Resource#IN          |  |   

