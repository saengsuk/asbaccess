## Usage Instruction

- Use Pipenv to install Ansible and its dependencies.
- A password is kept in the secret file and will need to be used to unlock or decrypt the content of the file.
- Please visit this guide on how to use ansible-vault https://docs.ansible.com/ansible/latest/user_guide/vault.html

## Example usage

#### To See the content of asbsk-device.yml

- ansible-vault view --vault-id asbsk@asbsk.secret asbsk-devices.yml

#### To decrypt the content of asbsk-device.yml

- ansible-vault decrypt --vault-id asbsk@asbsk.secret asbsk-devices.yml

## Secret file checksum

| File         | SHA1                                     |
| ------------ | ---------------------------------------- |
| asb.secret   | 9fc046f07db8e6abb4c8bde47adee00c4c86f46f |
| asbsk.secret | b491cdf46fccebe8b7957d1dee42562cce5b6543 |
| asbgv.secret | 47c239a54f4c3c307dcc6ae347908d35c7a4fd21 |
