Docker Image with simple Python-Flask Application
https://github.com/sebinxavi/Docker-Image-Of-Simple-Python-Flask-Application

Steps for build:
1. To create helm repo
2. helm create python-docker-example
3. change the values.yml files accordingly.


To make konvoy.tech (valid till March end) endpoint work with certmanger http01 ,
1. Get the Name server information from domain.com (konvoy.tech)
2. Create NS record Type in Route53 with the name servers from above domain and create  it in the new hosted zone
3. Now create a A record with ip address mapping to the ingress external ip (get it from ping external ip url)
4. example; ping a2e9c8863ffc64a0ea2e109e512e3f65-67861c8a3b96ddb4.elb.us-west-2.amazonaws.com


