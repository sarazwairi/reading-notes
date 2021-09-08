# API Deployment

## Django Settings: Issues

* Different environments.
* Sensitive data.
* Sharing settings between team members
* Django settings are a Python code. 

### 12 Factors is a collection of recommendations on how to build distributed web-apps that will be easy to deploy and scale in the Cloud. It was created by Heroku, a well-known Cloud hosting provider.

## Naming Conventions: Rules

* Give meaningful names to your settings.
* Always use the prefix with the project name for your custom (project) settings.
* Write descriptions for your settings in comments.

### Django Settings: Best practices

* Keep settings in environment variables.
* Write default values for production configuration (excluding secret keys and tokens).
* Don’t hardcode sensitive settings, and don’t put them in VCS.
* Split settings into groups: Django, third-party, project.
* Follow naming conventions for custom (project) settings.

## SSH

SSH, or Secure Shell, is a remote administration protocol that allows users to control and modify their remote servers over the Internet. 

### There are three different encryption technologies used by SSH:

* Symmetrical encryption
* Asymmetrical encryption
* Hashing.

### Symmetric encryption is a form of encryption where a secret key is used for both encryption and decryption of a message by both the client and the host. 
### Asymmetrical encryption uses two separate keys for encryption and decryption. These two keys are known as the public key and the private key. Together, both these keys form a public-private key pair.