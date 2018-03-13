# ad_nslcd
Linux integration for AD using nslcd. Features linux system, sudo, SSH Password, SSH Public Key Authentication


# How to apply
  1. Install puppet. This is tested with puppet3\
     `yum install puppet3`
     
  2. This integration stdlib from puppetlabs. Some distribution have this already, if not, install it\
     ```
     #Check if you have puppet stdlib
     puppet module list
     
     #Install it
     pupppet module install puppetlabs-stdlib --version 4.24.0
     ```
  3. Clone this repo
     `git clone https://github.com/VoyagerInnovations/ad_nslcd.git`
  4. Update adnslcd.pp with the correct parameters and credentials
  4. Apply the manifest file\
     `puppet apply adnslcd.pp`
