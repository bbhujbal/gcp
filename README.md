#kubectl get po -o wide -o=custom-columns=NAME:.metadata.name,IP:.status.podIP,Node:.spec.nodeName
