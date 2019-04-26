# QpesaCoin-Blockchain-Explorer
Block explorer for QpesaCoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon QpesaCoind. It should be accessible from the Internet. Run QpesaCoind with open port as follows:
```bash
./QpesaCoind --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=21896
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

### Development
Devs:
    @devopsralf

Donate: [QPSA] QPSATsp3pDuHRF8ex8mdij4Sf1tFQjTdm3JneLkZdovw9VrgKaVtQqrbahczFdrEkRb8cCNhPP1LEeW9kpyo1AS42choKW6cHm

### Note

A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
