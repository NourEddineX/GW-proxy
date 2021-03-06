<table>
<tr><th>Public OVA Download Links</th></tr>
<tr><td> 

|OVA Name           |       Download Link                     |  OVA Size |      Description                    |        Deployment Instructions                    |   
|--	                |--	     	            |--                    |--	     	                              |--	     	                              |
|Proxy Rebuild	    |[Proxy OVA](https://glasswall-sow-ova.s3.amazonaws.com/vms/proxy-rebuild/proxy-rebuild.ova?AWSAccessKeyId=AKIA3NUU5XSYVTP3BV6R&Signature=nXPDF0GWh0%2FcaWrU6o4pzoHBTwg%3D&Expires=1607523025) |4.3 GB                          |Kubernetes based reverse proxy setup|[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/proxy-rebuild.md) |  	   
|HAProxy-ICAP	    |[HAProxy-ICAP OVA](https://glasswall-sow-ova.s3.amazonaws.com/vms/HAProxy-ICAP/HAProxy-ICAP.ova?AWSAccessKeyId=AKIA3NUU5XSYVTP3BV6R&Signature=CqsLBjhKimAVBhoSaRFhLOEvvzg%3D&Expires=1607257398)|2.5 GB   	              |Load balancer for ICAP servers |[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/HAProxy-OVA.md) |    	
|HAProxy-Web	    |[HAProxy-Web OVA](https://glasswall-sow-ova.s3.amazonaws.com/vms/HAProxy-WEB/HAProxy-WEB.ova?AWSAccessKeyId=AKIA3NUU5XSYVTP3BV6R&Signature=YTwfynC4zpSwaYP0UFXAQyLExsU%3D&Expires=1607495696)|2.4 GB  	                  |Load balancer for proxied websites |[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/HAProxy-web-OVA.md) |    	
|Minio Server offline       |[Minio Server OVA](https://glasswall-sow-ova.s3.amazonaws.com/vms/Minio-Server/minio-server.ova?AWSAccessKeyId=AKIA3NUU5XSYVTP3BV6R&Signature=FZXLT6NqZyMMzOkkHEVD4T8K%2FzI%3D&Expires=1607569950)|1.9 GB	                  |Minio server virtual machine |[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/minio_server.md) |    
|ICAP Server        |[ICAP Server OVA](https://glasswall-sow-ova.s3.amazonaws.com/vms/ICAP-Server/k8-icap-sow.ova?AWSAccessKeyId=AKIA3NUU5XSYVTP3BV6R&Signature=O4IqjG8fTh5%2FOr%2Flo%2Bub1SmfYX4%3D&Expires=1607644772)|4.6 GB                      |Kubernetes based ICAP server/CDR engine|[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/icap-server-ova.md) |  
|Wordpress          |[Wordpress OVA](https://glasswall-sow-ova.s3.amazonaws.com/vms/wordpress/Glasswall-wordpress.ova?AWSAccessKeyId=AKIA3NUU5XSYVTP3BV6R&Signature=QwJ78so5inpe%2F4iVG8sqUTB5%2B0Q%3D&Expires=1607568331)|1.7 GB                        |Offline wordpress virtual machine|[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/create_export_import_wordpress_site.md) |  
|Shared storage            |[Shared Storage](https://glasswall-sow-ova.s3.eu-west-1.amazonaws.com/vms/TrueNAS/TrueNAS.ova?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA3NUU5XSYVTP3BV6R%2F20201202%2Feu-west-1%2Fs3%2Faws4_request&X-Amz-Date=20201202T080159Z&X-Amz-Expires=604800&X-Amz-SignedHeaders=host&X-Amz-Signature=cd47c612a7d2041ab095cee6947c5d9f412f4d6b01b3717988fe3f065622a210)|1.7 GB|Shared storage VM|[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/TrueNas-OVA.md) |  
|File-drop            |[File-drop](https://glasswall-sow-ova.s3-eu-west-1.amazonaws.com/vms/SOW-REST/sow-rest.ova)|1.8 GB|File drop with REST API|[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/SOW-REST.md) |  
|Monitoring             |[Monitoring](https://glasswall-sow-ova.s3.amazonaws.com/vms/visualog/visualog.ova?AWSAccessKeyId=AKIA3NUU5XSYVTP3BV6R&Signature=B3p%2FTRsLKyl6Pij6JoKvI4g10cw%3D&Expires=1607669097)|3.8 GB|ICAP monitoring tool|[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/monitoring-ova.md) |  
|Gov.uk offine             |[GOV.uk](https://glasswall-sow-ova.s3-eu-west-1.amazonaws.com/vms/gov-uk/gov.uk.local.ova)|1.5 GB|Offline Gov.uk website virtual machine|[How to use](https://github.com/k8-proxy/GW-proxy/blob/GINAGC-patch-27/OVAs-creation/create_gov_uk_offline_site.md) | 
|Traffic Gen             |NA|   |ICAP performance solution OVA|[How to create OVA](https://github.com/k8-proxy/aws-jmeter-test-engine/blob/master/jmeter-icap/instructions/How-to-create-OVA.md)|  
|Traffic Gen             |[Traffic Gen](https://glasswall-sow-ova.s3-eu-west-1.amazonaws.com/vms/Traffic-Generator/Traffic-Generator.ova)|2.6 GB|ICAP performance solution deploy OVA|[How to deploy OVA](https://github.com/k8-proxy/aws-jmeter-test-engine/blob/master/jmeter-icap/instructions/How-to-Deploy-OVA.md) |  
|Traffic Gen             |NA|   |ICAP performance solution load|[How to generate load](https://github.com/k8-proxy/aws-jmeter-test-engine/blob/master/jmeter-icap/instructions/How-to-Generate-Load-with-OVA.md) |
|Support             |[Support](https://glasswall-sow-ova.s3-eu-west-1.amazonaws.com/vms/SupportServer/SupportServer01.ova)|2.8 GB  |  |[How to use](https://github.com/k8-proxy/GW-proxy/blob/master/OVAs-creation/SupportServer.md) |  
|Linux desktop             |TBD|  |  |[How to use](https://github.com/k8-proxy/GW-proxy/blob/master/OVAs-creation/Linux-Desktop.md) |  


</td></tr>

</table>

