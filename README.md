# GitHub-ES-Demo-Setup

### 1. Get a trial license 

In order to evalute GitHub Enterprise Sever for free, you can opt for a trail license from [here](https://enterprise.github.com/trial) and test the features. It's a 45-day trial to evaluate GitHub Enterprise Server. Your trial will be installed as a virtual appliance, with options for on-premises or cloud deployment. For a list of supported visualization platforms, see ["setting up a GitHub Enterprise Server instance"](https://docs.github.com/en/enterprise-server@3.3/admin/installation/setting-up-a-github-enterprise-server-instance)

For deatiled recommendations see the [installation guide](https://docs.github.com/en/enterprise-server@3.3/admin/installation)

### 2. Login to your account

- Once you sign-up, you will receive an email from GitHub with instaructions on how to set-up your instance. 

- You can sign in to your account [dashboard](https://enterprise.github.com/login)

- You will be able to download your license key by going to Download

<img src= /images/download.jpg>

- Download the license key and you can either deploy your instance on-premsies or in the cloud

### 3. Pick the installation type

- I went ahead with a **'New Install'**

<img src= /images/installation_type.jpg>

### 4. Deployment 

- In the next step, populate the information in the template and review+create
<img src= /images/deploy-template.png>


#### Deployed resources 
<img src= /images/deployed-resources.png>

### 5. Create an Admin account and an Org

- Copy the DNS name of the VM instance and open in the browser 

- It is going to ask you to create an admin account and will also ask if you want to create an Org

<img src= /images/admin-account.png>

Created org will look similar to this - 

<img src= /images/demo-org.png>

- Once you create an admin account, it will take you to the management console where you will enable actions, packages for your Org

### 5. Enable Actions and Packages

- Login to the management console which can also be access via https://DNS-name:8443/setup/settings

- Enable GitHub actions, in order to save the settings successfully you will need to create a Storage account and put the connection string under Artifact & Log Storage option and 'Click storage settings' 

- Do the same for packages and save settings whioch is important else it is not gonna save the settings 

<img src= /images/enable-action.png>

<img src= /images/enable-packages.png>



