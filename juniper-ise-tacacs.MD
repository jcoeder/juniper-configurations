# Router Config

```tacplus-server {
    172.16.100.50 {
        source-address 172.16.100.30;
    }
    172.16.222.51 {
        source-address 172.16.100.30;
    }
}
login {
    }
    user op {                           
        uid 2004;                       
        class operator;                 
    }                                   
    user ro {                           
        uid 2003;                       
        class read-only;                
    }                                                               
    user su {                           
        full-name local-user-name;      
        uid 2002;                       
        class super-user;               
    }                                   
}```
