# My Ansible Playbooks 
Hello any who stumble Accross this.
This Repo is primarily my steps as I pick up Ansible with a Pi cluster and get it working. 
This intial commit are my first 3 that I ran straight out of the bag, I set up a base Raspbian OS and flashed them with the same username and password combo, and enabled SSH. And right off the bat, Ansible is in play. 
I set up a Fedora VM as a control center for Ansible as, for the immediate future, Ansible will primarily be for the Pis

# Current Status
Currently these are just 3 setup Playbooks,
1. Create a dediicated "Ansible User"
2. reboot all of the Pis
3. Configure all of the Pis to control their PoE HAT fans. 

These are just my initial setup so as I break things, their initial setup can be quickly restored and be managed by Ansible.
I will be getting Ansible Vault set up here soon to make credential management a little more streamlined.
# Future
I am looking at Kubernetes and other  container  platforms to get started on the Pi and help me not just wildly commit resources
For now I am learning about the Pi's functions and just getting the hang of what I can do with a small linux box with resource limits forced on me vs being able to reassign some pretty generous resources from a larger server. 

If you actually found these and they helped, great! Thanks for checking it out and I'm more than welcome to input. 