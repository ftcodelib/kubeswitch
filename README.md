# Kubeswitch

## Install the script
1. Download the script

2. Make it executable.
`$ chmod +x kubeswitch`

3. Create a tools directory. (optional).
`$ mkdir ~/tools`

4. Add below line into your .bashrc or .zshrc (optional).
`export PATH=$HOME/tools/:$PATH`

## Using kubeswitch

1. To add new kubeconfig or edit existing kubeconfig.
`kubeswitch {add|edit} <your_preferred_config_name>`

2. To switch config 
`kubeswitch set <your_preferred_config_name>`

3. To clear/unset config 
`kubeswitch clear`

4. To get your current config or kube config context
`kubeswitch {status|context}`

5. To list all available config 
`kubeswitch list`

6. To remove config file
`kubeswitch {rm|delete} <target_config_name>`
