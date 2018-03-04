# HashiCorpVault-Docker-Ansible
### Shows how to deploy a Vault docker container with Ansible
 
### How to Deploy

- Before run, open the `deploy/hosts` file and add in the host you are deploying to.
- Go to `deploy` folder and run: 

```
> ansible-playbook install_vault.yml -i hosts
```

## License

This project is licensed under the **Apache License**. This means that you can use, modify and distribute it freely. See [http://www.apache.org/licenses/LICENSE-2.0.html](http://www.apache.org/licenses/LICENSE-2.0.html) for more details.