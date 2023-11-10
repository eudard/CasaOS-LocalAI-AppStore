**This app is possible to install as stack into Portainer**

For now I can't find a way to install it as CasaOS app, but I'm working on it.

## Installation

1. Install Portainer as CasaOS app
2. Open Portainer and go to `Stacks` section
3. Click `Add stack` button
4. Fill the form with the following data:
   - Name: `Metabase`
   - Web editor: `Uncheck`
   - Stack file: `Copy and paste the content of metabase-portainer.yml file`
5. Click `Deploy the stack` button and wait for some minutes the installation to complete
6. Open Metabase app in `[CasaOS_IP:6400]` like `192.168.1.50:6400`
