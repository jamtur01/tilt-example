k8s_yaml('k8s-pod.yaml')

docker_build('jamtur01/tilt-mate', 'mate')

k8s_resource('mate', port_forwards=3000)
