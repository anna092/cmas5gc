## What is CMAS 5GC

The objective of this project is to implement the warning message replacement function in the 5GC's AMF, as defined by 3GPP 23.041 for 5G cell broadcast technology.

The 5G core network services for this project are developed based on free5gc v3.3.0.

For more information, please refer to [free5GC official site](https://free5gc.org/).

<p align="center">
<a href="https://free5gc.org"><img width="40%" src="https://forum.free5gc.org/uploads/default/original/1X/324695bfc6481bd556c11018f2834086cf5ec645.png" alt="free5GC"/></a>
</p>


## Contributions and Completed Features

* Developed NonUeN2MessageTransfer API 
* Developed Write-Replace Warning Request 
* Supported Warning message delivery procedure in NG-RAN 
* Supported CBCF/PWS-IWF access via the N50 interface
* Supported NG-RAN access via the N2 interface

<p align="center">
  <img src="https://github.com/anna092/cmas5gc/assets/113874435/5ef0537b-e56d-48b0-94c9-188329b1b5a7" alt="PWS_thesis-amf"/> 
</p>

## Steps to build AMF
* Download the dependency in NFs/amf/
```
go get go.mongodb.org/mongo-driver/mongo
go get github.com/warthog618/sms
```

## More Information

For more details on connecting cell broadcast services to 5GC, please check our [5G CBS](https://github.com/anna092/cbs5g.git)
