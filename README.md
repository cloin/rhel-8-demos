# rhel-8-demos

I use Vagrant and Virtualbox to create 3 minimal VMs which I use to demonstrate various RHEL 8 additions and changes. My [VagrantFile](https://github.com/cloin/rhel-8-demos/blob/master/VagrantFile) uses the [Ansible provisioner](https://www.vagrantup.com/docs/provisioning/ansible.html) to create an Ansible inventory that I can use to run my playbooks on. 

Each demo has it's own repository:

### [cloin/ansible-cockpit: Cockpit roles for nodes to report to single master](https://github.com/cloin/ansible-cockpit)
![session recording gif](https://raw.githubusercontent.com/cloin/ansible-cockpit/master/cockpit-dashboard.gif)

### [cloin/session-recording: Configure Cockpit for session recording](https://github.com/cloin/session-recording)
![cockpit dashboard gif](https://raw.githubusercontent.com/cloin/session-recording/master/cockpit-session-recording.gif)

