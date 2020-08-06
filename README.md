# Files to upload to Vagrant box
All these files should be uploaded to the root of your vagrant box.

# Supervisor
You may need to adjust the paths in the `.conf` files to reflect your own setup.

# Nginx
You may need to adjust the root in file `/etc/nginx/sites-available/keystone.test`. If you do not access Keystone.guru
locally through `https://keystone.test/` you also need to rename that file and adjust references to it as appropriate.
It should match whatever you've set in your `Homestead.yaml` under `sites:`.