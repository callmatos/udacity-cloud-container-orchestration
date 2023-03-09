
## Exercise Starter Code
The current folder conatins the following starter code for the classroom exercises:
```bash
.
├── Vagrantfile        # Vagrant exercise
├── go-helloworld      # Docker and Kubernetes exercise
│   ├── README.md
│   └── main.go
├── manifests           # yaml files to configuration Kubernet cluster
│   ├── configmap.yaml  # yaml configuration information
│   ├── deployment.yaml # yaml deployment of image, spec
│   ├── namespace.yaml  # yaml definition of ns
│   └── service.yaml    # yaml to definition of service (port etc)
└── python-helloworld  # Docker walkthrough code  
    ├── app.py
    └── requirements.txt
```


**Note**: the specified `config.vm.box_version` in the Vagrantfile updates with time. You will have to change it from `212` shown in the demo video above to a newer version. When a particular version used in Vagrantfile becomes deprecated, the command prompt will show you all available newer versions. 


