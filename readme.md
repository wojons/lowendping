## LowEndPing Network Status

LowEndPing is a simple network query script.

Installation:

- Install Composer
- Download the contents and extract into a directory
- Run "composer install" in that directory
- Run "php artisan migrate" to initialize the database
- Install the python script on the servers you want (see below)
- Try it out!

Python script installation:

- Install python-pip
- Run 'pip install sh' (the required shell wrapper)
- Update the information in lepconf.py to point to your server
- Firewall the script using iptables or your method of choice (it has no authentication, just block port 12337 to all but your main node)
- Run 'python lep.py' (It is recommended

### License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

LowEndPing is also open-source and licensed under the same license.