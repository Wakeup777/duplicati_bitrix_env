# duplicati_bitrix_env
Automatic deployment of Duplicati backup software in a Bitrix environment. Be careful, this script will only work for this environment.


how is it work ?

1. First, rename "example_host.ini" to "host.ini"
2. Second, write ip your server in host.ini
3. 3rd, write in console "ansible-playbook role_duplicati_bitrix.yml"
4. 4th, wait a couple minutes
5. 5th, use it