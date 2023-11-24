Steps  

d build -t stanislavstarodub/demo1:v1.0.0 .  
d login  
d push stanislavstarodub/demo1:v1.0.0  

k create deploy demo1 --image stanislavstarodub/demo1:v1.0.0  
k get po -o wide
k expose deploy demo1 --port=8080 --type=NodePort  
k get svc  
k port-forward service/demo1 8080